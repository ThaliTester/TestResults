#### Test 1374640318f8a044_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1374640318f8a044/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/4259D386-8B17-469D-B595-EE650798DDF3/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/4259D386-8B17-469D-B595-EE650798DDF3/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1374640318f8a044/build_ios/ThaliTest.app"
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Current executable set to '/Users/thali/Github/CI/builder/builds/1374640318f8a044/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59996"
,(lldb)     command script import "/tmp/4259D386-8B17-469D-B595-EE650798DDF3/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
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
,2017-08-24 14:47:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:47:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:47:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:47:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:47:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:47:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:47:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:err,orHandler:) Peer(uuid: "C6C0AC80-305D-4FB9-8E15-D55849D23FC2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C6C0AC80-305D-4FB9-8E15-D55849D23FC2
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:50AACFF4-D680-4958-A7C8-3CFAD2138F7C
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EDFB227A-,5F38-4C32-A6AB-C8344AC5E789
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C8E4E7D2-FA8E-49AA-AED1-C60DD41BBE54", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:C8E4E7D2-FA8E-49AA-AED1-C60DD41BBE54
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8E4E7D2-FA8E-49AA-AED1-C60DD41BBE54:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8E4E7D2-FA8E-49AA-AED1-C60DD41BBE54", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-08-24 14:47:54 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.540666997432709
,2017-08-24 14:47:54 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-08-24 14:47:54 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C8E4E7D2-FA8E-49AA-AED1-C60DD41BBE54:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C8E4E7D2-FA8E-49AA-AED1-C60DD41BBE54", generation: 0)
,2017-08-24 14:47:57 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-08-24 14:47:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-08-24 14:47:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-08-24 14:47:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-08-24 14:47:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-08-24 14:47:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-08-24 14:48:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-08-24 14:48:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-08-24 14:48:01 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-08-24 14:48:01 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-08-24 14:48:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:48:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:48:39 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-08-24 14:48:39 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-08-24 14:48:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
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
,2017-08-24 14:48:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-08-24 14:48:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-08-24 14:48:58 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 51 participant data matches
,ok 52 test participant has uuid
,ok 53 participant data matches
,ok 54 test participant has uuid
,ok 55 participant data matches
,ok 56 own UUID is found from the participants list
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
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:49:02 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:84E15A81-D4D2-4C63-864C-0CD648BDE498
[ThaliCore] Browser.startListening
2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:49:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:49:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2F04E697-7CCB-49E7-B505-A7AF3C9CB853
[ThaliCore] Browser.startListening
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "114AD161-8C92-4A02-ADD9-53ABC5E0CAA4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:114AD161-8C92-4A02-ADD9-53ABC5E0CAA4
2017-08-24 1,4:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:114AD161-8C92-4A02-ADD9-53ABC5E0CAA4
2017-08-24 14:49:05 - DEBUG tha,l,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisi,ngAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "53A134FC-D311-43C1-995F-B33DE434AB4B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:53A134FC-D311-43C1-995F-B33DE434AB4B
2017-08-24 1,4:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "53A134FC-D311-43C1-995F-B33DE434AB4B", generation: 1)
[ThaliCore] ,A,dvertiser.startAdvertising with peerID:53A134FC-D311-43C1-995F-B33DE434AB4B
2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:06 - INFO thali,Mobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})',
2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:53A134FC-D311-43C1-995F-B33DE434AB4B
,[ThaliCore] Advertiser.stopAdvertising() peerID:53A134FC-D311-43C1-995F-B33DE434AB4B
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
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4361EF87-5749-4B4B-BADE-9D3B1EE2E99F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4361EF87-5749-4B4B-BADE-9D3B1EE2E99F
2017-08-24 1,4:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2E8CA379-8F21-4FA4-8BCE-05DA5D7E4672
[Thali,Core] Browser.startListening
2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:49:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:11 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0CEB9198-C417-4D4F-901C-D334A7FD5AF8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0)
,ok 76 peers must be an array
,ok 77 peers must not be zero-length
,ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 79 peerIdentifier must be a string
,ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4361EF87-5749-4B4B-BADE-9D3B1EE2E99F
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1FFA4D95-6464-4803-8737-E537C6B4DECB
,2017-08-24 14:49:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4A5D4407-7425-41D9-94AF-6EE52E81E892
,[ThaliCore] Browser.startListening
,2017-08-24 14:49:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:49:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:49:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0CEB9198-C417-4D4F-901C-D334A7FD5AF8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
,2017-08-24 14:49:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0CEB9198-C417-4D4F-901C-D334A7FD5AF8","generation":0}'
,2017-08-24 14:49:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0CEB9198-C417-4D4F-901C-D334A7FD5AF8 (syncValue: GN7GPNr1tC7kolFEkXNUV2TDHAwAeV5O)'
,2017-08-24 14:49:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0CEB9198-C417-4D4F-901C-D334A7FD5AF8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:49:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A0607900-813D-4C11-B1D3-06B66F9F9C6D","generation":0}'
2017-08-24 14:49:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-,24 14:49:12 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A0607900-813D-4C11-B1D3-06B66F9F9C6D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A0607900-813D-4C11-B1D3-06B66F9F9C6D", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:0CEB9198-C417-4D4F-901C-D334A7FD5AF8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2B2E31C8-0CC3-4F27-8F27-FCADD,BFCDA78:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1FFA4D95-6464-4803-8737-E537C6B4DECB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E3D14BF0-885E-42DE-AEF8-51DA6C19C621","generation":0}'
2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9DD4F87E-D15D-4AF3-A20F-12F9AD90F56A
[ThaliCore] Advertiser: session connected Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9DD4F87E-D15D-4AF3-A20F-12F9AD90F56A state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:0CEB9198-C417-4D4F-901C-D334A7FD5AF8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0C,EB9198-C417-4D4F-901C-D334A7FD5AF8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0CEB9198-C417-4D4F-901C-D334A7FD5AF8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:49:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GN7GPNr1tC7kolFEkXNUV2TDHAwAeV5O","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:49:15 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GN7GPNr1tC7kolFEkXNUV2TDHAwAeV5O', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:49:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:49:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78 (syncValue: x4WXy4ekp9MT154HUcD5qba,d6LQnXNji)'
2017-08-24 14:49:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B2E31C8-0CC3-4F27-8F27-FCADD,BFCDA78:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:49:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:0CEB9198-C417-4D4F-901C-D334A7FD5AF8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42BA428F-605E-484E-AD76-070619DC0473
[ThaliCore] Advertiser: session connected Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:42BA428F-605E-484E-AD76-070619DC0473 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9DD4F87E-D15D-4AF3-A20F-12F9AD90F56A
,[ThaliCore] Session.session(_:peer:didChange:) peer:9DD4F87E-D15D-4AF3-A20F-12F9AD90F56A state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63253
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"x4WXy4ekp9MT154HUcD5qbad6LQnXNji","error":null,"portNumber":63253}'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'x4WXy4ekp9MT154HUcD5qbad6LQnXNji', error: 'null', listeningPort: '63253''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:42BA428F-605E-484E-AD76-070619DC0473
,2017-08-24 14:49:18 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
ok 85 listening port should not be 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:42BA428F-605E-484E-AD76-070619DC0473 state: connecting -> connected
,# teardown
,2017-08-24 14:49:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] Session.session(_:peer:didChange:) peer:42BA428F-605E-484E-AD76-070619DC0473 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:42BA428F-605E-484E-AD76-070619DC0473
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:49:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:1FFA4D95-6464-4803-8737-E537C6B4DECB
,[ThaliCore] Session.session(_:peer:didChange:) peer:9DD4F87E-D15D-4AF3-A20F-12F9AD90F56A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "1FFA4D95-6464-4803-8737-E537C6B4DECB", generation: 0)
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:49:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63253
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-24 14:49:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"x4WXy4ekp9MT154HUcD5qbad6LQnXNji","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:42BA428F-605E-484E-AD76-070619DC0473
,[ThaliCore] Session.deinit peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D
2017-08-24 1,4:49:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:16F78A91-FC3A-4ECD-A60E-4E0540FAA0A8
,[ThaliCore] Browser.startListening
,2017-08-24 14:49:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:49:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E3D14BF0-885E-42DE-AEF8-51DA6C19C621","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E3D14BF0-885E-42DE-AEF8-51DA6C19C621 (syncValue: UR3tyqoALUyR3AAVc17ijRFO3xIyNUKL)'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78","generation":0}'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
2017-08-24 14:49:20 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A","generation":0}'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF3C2297-B546-4712-88B9-DA70154DC511","generation":0}'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E3,D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E3,D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E3,D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "E3D14BF0-885E-42DE-AEF8-51DA6C19C621", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:E3D14BF0,-885E-42DE-AEF8-51DA6C19C621 error: max retries exceeded
2017-08-24 14:49:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UR3tyqoALUyR3AAVc17ijRFO3xIyNUKL","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UR3tyqoALUyR3AAVc17ijRFO3xIyNUKL', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:49:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78 (syncValue: 5XyvvSu,DG1I5Qdp2C9fXcSsYy7DIlUSa)'
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2B2E31C8-0CC3,-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E3D14BF0-885E-42DE-AEF8-51DA6C19C621:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CD220B91-3711-48B7-AA0B-716EED0F01D0
[ThaliCore] Advertiser: session connected Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CD220B91-3711-48B7-AA0B-716EED0F01D0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2B,2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CD220B91-3711-48B7-AA0B-716EED0F01D0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD220B91-3711-48B7-AA0B-716EED0F01D0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CD220B91-3711-48B7-AA0B-716EED0F01D0
[ThaliCore] Session.startOutputStream(with:) peer:CD220B91-3711-48B7-AA0B-716EED0F01D0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1, [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
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
,2017-08-24 14:49:36 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-24 14:49:36 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-24 14:49:36 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-08-24 14:49:36 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
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
2017-08-24 14:49:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5XyvvSuDG1I5Qdp2C9fXcSsYy7DIlUSa","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:49:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5XyvvSuDG1I5Qdp2C9fXcSsYy7DIlUSa', error: 'Connection could not be established', listeningPort: '%s''
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE
[ThaliCore] Advertiser: session connected Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,2017-08-24 14:49:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-24 14:49:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A (syncValue: ZVkLqxdB60Loipzc8mG6ieHeFdeiqHf0)'
,2017-08-24 14:49:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2B2E31C8-0CC3-4F27-8F27-FCADDBFCDA78:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE
[ThaliCore] Session.session(_:peer:didChange:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63261
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ZVkLqxdB60Loipzc8mG6ieHeFdeiqHf0","error":null,"portNumber":63261}'
2017-08-24 14:49:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Z,VkLqxdB60Loipzc8mG6ieHeFdeiqHf0', error: 'null', listeningPort: '63261''
,Connecting to the localhost:63261
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
Connected to the localhost:63261
,2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
[ThaliCore] Session.session(_:peer:didChange:) peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE state: connecting -> connected
,2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE
[ThaliCore] Session.startOutputStream(with:) peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-08-24 14:49:45 - DEBUG testThaliMobileNative: 'Server data flushed'
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
# teardown
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-08-24 14:49:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:49:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B3374CEC-5CAF-4EC9-8F24-18B03362EC6D
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:49:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 [3]
,[ThaliCore] BrowserManager.disconnect peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63261
,[ThaliCore] Session.disconnect() peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:49:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:49:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD220B91-3711-48B7-AA0B-716EED0F01D0 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "B3374CEC-5CAF-4EC9-8F24-18B03362EC6D", generation: 0)
,[ThaliCore] Session.deinit peer:1F0D248B-C51F-46F4-85D5-FAF32D29B6EE
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DD12190F-C11B-4D3D-90CA-E076C0040F6F
2017-08-24 1,4:49:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:49:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F002F8B7-4015-4228-B6C2-89DB7A04875D
[ThaliCore] Browser.startListening
2017-08-24 14:49:46 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:49:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:49:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListe,ningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
2017-08-24 14:49:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A","generation":0}'
2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A, (syncValue: eVoiy7qq0tXxGUQsNH5ZOSFYBfPIYsri)'
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retry,Count:completion:) Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[Thal,iCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF3C2297-B546-4712-88B9-,DA70154DC511","generation":0}'
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CF3C2297-B546-4712-88B9-DA70154DC511:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CF3C2297-B546-4712-88B9-DA70154DC511", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
2017-08-24 14:49:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1A2F523B-551F-43F6-8F63-E9BA6B74AA01","generation":0}'
2017-08-24 14:49:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:49:47 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD12190F-C11B-4D3D-90CA-E076C0040F6F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
,2017-08-24 14:49:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49113C2E-45AB-4903-A759-BC5216FA0D18","generation":0}'
,2017-08-24 14:49:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:49:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A4,C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A4,C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A4,C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A4,C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:A4C1EAA2,-78F8-4D2B-A7A8-6D73185C810A error: max retries exceeded
2017-08-24 14:49:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eVoiy7qq0tXxGUQsNH5ZOSFYBfPIYsri","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eVoiy7qq0tXxGUQsNH5ZOSFYBfPIYsri', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:49:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1A2F523B-551F-43F6-8F63-E9BA6B74AA01 (syncValue: HYqs3TT,TYBzRKQBKUHtkTaMHPsPRJ1qN)'
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:A4C1EAA2-78F8-4D2B-A7A8-6D73185C810A:0
[ThaliCore] BrowserRelay.deinit
2017-08-24 14:49:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
[ThaliCore] Advertiser: session connected Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "1A2F523B-551F-43F6-8F63-E9BA6B74AA01", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63278
,2017-08-24 14:50:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HYqs3TTTYBzRKQBKUHtkTaMHPsPRJ1qN","error":null,"portNumber":63278}'
,2017-08-24 14:50:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HYqs3TTTYBzRKQBKUHtkTaMHPsPRJ1qN', error: 'null', listeningPort: '63278''
,Connecting to the localhost:63278
,Connecting to the localhost:63278
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
Connecting to the localhost:63278
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:1A2F523B,-551F-43F6-8F63-E9BA6B74AA01:0
,Connected to the localhost:63278
,Connected to the localhost:63278
,Connected to the localhost:63278
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [3, 4, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 4, 5, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
,ok 92 correct string length
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-08-24 14:50:00 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
[ThaliCore] Session.startOutputStream(with:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
[ThaliCore] Session.startOutputStream(with:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8, [3, 4, 5, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
[ThaliCore] Session.startOutputStream(with:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [3, 4, 5, 6, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:4 [3, 5, 6, 7, 8, 9]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [3, 5, 7, 8, 9]
,ok 94 got the same data back
,ok 95 got the same data back
,ok 96 got the same data back
,# teardown
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server received (9855 bytes):'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server received all data: H3nWuwRwUbdNihQWhND6ptWBI3KtPvaRX5Xy5oLERPqAfhox5z67Ascb6D3OjqcN8s74Hlj7Ct6sRvyC9VOemnwzv270Z0hs68OhVrAat5IWLPmxzTg9FMC2rBgyvS1AYy0z1wJSh9B18Ex2hWl06nw0cssxcLiXyqhQiphOIewFblmUqc,vIfE5YTP87oJh1Jt2C3Ra722kqTfjVWRFEHQ15lq6GNgzP4f7C6YZrJUyAK633tMhIOyaRTMpfv9Xv7GvdDcfQFKxUC2CygVwHJQ8yTfXjIniweTCtAqjtxDM0nNiq06jqsOptIqRXiNMCnEKGRG5ecugMrOizvlWX40nA5oeAut9EIaRLAv5oOdMkm2nOlJkzXAk89X2qNA5WFrt6oAmzRUuTyRPLh6JW81Tx1hRimX2PEuukiVr7q6KCKBNwOv,xQM5togLobHk1vlVAR4uTlUQTCDHl9Iq8NKPx6b3HANXpHI400KuCoUO07HkOTGHGrEZkaBUDLZ8OJnpUA8pUX5cndLz5v1Gbd7GIzrSATwYMJq8JlrUUXLayQKxvsvlqtwzMPWJYVrhE1Sf8uO5WJ5tQLsoi2LKAdy1aztaRpPheTEbtXm8s8MMD4PQBN36R9K8Idks7mxqEvvC1ALl4XuhKAvAslWjAopDVd4Pzg9wMwqEumpnVBWSYpcy9rQb,UQrjHBDmYNsGAXjpzeMJ8lqPNSN8h8gSYk7NsIdt8PihYF7iPoIlCU5ylMrk8OkOr2X98oUUwfcLntj17fGwcjC5HUjZm6Wsx2Gvm7er89WErdQY1Qdv6iwaOIXgeLZvMhvYF3pYFHJ006LZekXCwZnTMLflH1uRDfvJ0jihf87ENIU3R5K57nvlNBrVDbMMmyWYiCe8hkzyPPetoF9jFdPD9NTHteZyBlsqfCnn5Biu2LNiJ8ZLP7aqnJVE9sE4,ucdlNfo6pVPY7Xq083RIY8dtum80PBmYQsT51DKCW68hyf5CExHTuhaUzcXLAjN58qlqnhKVEuRJWH3OzXyV6UfABdhtBvniqO4QMjZAZMJJwM4LaepKGMN5rLCNHzlPsgHvWpDPkDw3Vb6PhWY3rlMlwNaj0pyxGTYEXRsjE3sIwaxhEbQshdWPK0VslHh6V6pkC1uTpTVYdN7vKTapFyHdVsYcFB1rsu45JcZ0IerSnxgqci2RcxryywUY2U9g,BlY7IdcSOXF9CuxW0hid3M0QDqFatDTij9yX53OfaTN170ax3dEA85spyLNei9rruiAtnaVtffQ1N8MyhzDHMUgofWyX34mSkBbsutFLoiHmTi0rjgoEjmIXT0dUuQLTXlB35KhZacFJlr19LS7pdefj1Ry3dwcUyTHZyXGsJ55Hkw79SNALC9f2IWedQmdQEDQauCnSW73ZqeoGKlhB7IzT3QUOQ30YPknoU7E9bQ484YT0mxJltezQcN61zIuF,OVJRBkSxKN54bSiVtvmWvvMEwPxJnku7ZjpwXoLKsLRUSeTBcXMQ134FLL2fAyZoNio4Gx0vqso6uIjjNDcEzsABvc8WbVkJOk1Utcqog42AvfWcaNZB1OGCVWs0D6wW9prwb2MTd3OibxsixudHIAhwWv3ZdhYwleOU94SW9mAbKapJPnhSl8WyxHpN1UIjB5Wy2SW4vVIx14rYOj6pScUw1jvpfmzEEqAXJGOMxZVNYJazhmbP3gz7AgSRomcT,PmjPjkTkIUM9baKpnXeot5H9JuhAdIVDFo6Ql29SU4ciSHN8BSaGt6zAPsRHaYEM9qgZhNo3xTQahiDm5NNAHheecxxNGJmNhDpjM2ivSHFjpvUinACyarNjRtLF4ZLwMcEG3JEAD4AOCuHPIlEhlpgVXuLbsDQXeVOQxcQ9OZgW72vPYijJbIJwuuUlkN4Kr73eQsA7Jnhghox4WyH3CrTjO41N2gRWBpjPjbcL3nZ5iaB2cKAj6s5dTpGxqMGU,FyEqN6RJmlWgHJHCN2SNIhGA8dtGg3GtklcEZ3PI7CgLMk1nfDzNnIrxTgBlxpN3BZJVhd2AoqAQyBLQMUY22FPR3modMaSG7Nf90IEggAiIZ0yTXIoDb6FshgZwGSZylDL828gBKWgDr0WR0yrK9cGtaWMjBS3mXqF1XvM1nUiw6RTRYFm2QOmIo5HzozRmrFM8ydiouawScVm52nmn1YKFrtq5Y2u1PkbsQLikoEDKLmSaOHIMCenyzLzKYHdN,nouhpKxruL9DvB5jw5JrXKJZUiK5QwxE0lFhXW7r5hBzY6ubDdGSfDUwU9bXSVT3XjHtgsdOviK38306xillxhvVNFA08ysuPoTyuBdD9dGCzoXk0AXYb71juFQxx1s9TWOYUfqG1xNLevV6MXmk1PjGNAK07oS9ja12E98ZCP66Z6sve9FZP3fUVMI2m5ap7tIizx5lcYugDaovQqJvbSzYcclTCHA2DNwfs1g4QQuV6CR0GkRiGNGxgUgobaiD,hxfDI6AluVmgm22Af7I4bkx9sNp3NmfyfQWDiF43sSMOG8EjUfuY08CtdKRRIGvMDf2P1PkQAO7qKQCUDZ0FM7fmN2kq2SHV1OhhH6CuXq6UJsz0g8LkyHM8cX8KflzeBvYPM4pr13h4QysVmEyZFJt6bO5KicCcceklxqAMoEYtQGPAU8hllEVWInrptPIa2eqPvx6xaB2fGYwoMdJhVkmkuXt9cpSkLe8oGTo9GMYfwhtYMEwOiz24kIAmcxhY,uS8is6zoK8AlLzkPyN3IzBurS7yVmOUL63F6pzRql7tvG6MA9bMJwJMo6VNZjJEJtHv5oLJhy7dq4uu8Y9QieTuRjA3PrsmSsW2Lju5kB8NwJ4xvo2xrirgAA26MbvrPgRFUGHXsdPzxzDWafyh080g6gdVhUqaZ6d9mDTm8qd5yKwSZqNG7AFZ56if5VR6Y0N1T5DOoGzmCSqwsDyrrbhlxWQrAbD9C3QBnbeJiGoKKPLv3LXnQ2oSuBDEnE8s2,0vYNaI3y1OUvmKkALiIbE4XNmFwv9ZUTzZGBnE8wcXdl3Y9vxCQ6RQ8PRZ2Py99Sahdo5B0P48rn2yDZIOAkiP2y7lmiFd9eSetHbAOjY9x9Vt6bHsfc6kxkdDwCv3fFWTvuVF0F90UnYKIxxBpxiVSfOPRiCRnCcKfSAgMNkWJkZEhzJph7rvTIiRAZmMeKlbwpAZTzp8YQoE1lIuEMXY3naVBbUC65vynOb5Uk6wZ5WTIlMSiTGwGWplukLdwg,SC4ld7yc9ZyiuJGmD5vFqqjrRxAi1u9dsLvX73TEtNrBDF8yo1kCJXtRKTkGhVelz0Tu1Dvddgw26ftVSTEDW57TtnatY3FWchAng1fUsdulpZrjs6J2H2JzNa1umZxzxT5qpH7bflS5xtBDwVFoZaSZwmYDUQLHrtR1aDbLVGJLbM9qVWqK1wjEbK1RsP8RTiBHGOTuiBbXEX7ovhjm5UdbdItyzTTDwh7yVSfR1sKwBn2xoFhMZwlMGgMJ0ZEA,BHOBLxHoncjhcygsSVNT4d4ONu85tjIcoNgtyvHpQr8UXy7fpl7cfeMKmCZAvfe7PktrUjriz8xZV5OT3BXxUK99wUDTwtpby1VbU2i2BomcPNN2tQB7uKvgoSTTsB9JW4ro8ci53H7ZtXtXRLTma10jEjVRBvYmU2JtlnveZAslzvAJ5CbkBGxf7ZRxs4d0MvTUbzYtA7DcZxkgeWXaVKOi4pSi37h3a6n0EGmPCXjrSOR7b1dNSTBo72LXWdpi,UmsTCu3K3ZBkMLUjy4DvaJr9A2SyWmpVl30LnBF4soZLXy3EHbROk0iVS5iUvfN4kEQQLqbwexI2eIWTKiWc0PFizeK7BlSqJwEjJTR3wfH4DBqzc8BY8W7ek62DAH03zVWstQJfllDLLueB6SbyQrWDPwJC5EiRyxNpCMn31qk7tLcUOYT6qlUmHjpY4uboPGfhufzSohzPaCAC8kub8qJyMHdWoO4WMpwLYTaASvD3Tu9nh6XDpSwYDnnIaVAM,3tDc5aTDNyTkxkYJCp7Ajahosmq1ehQAI5zCwH7lPepQZY0lHS5Jt8lH7XyMBz8IcfL82ZgueksFibzZ56kJjv9iIXSSnJsE9h1Mp7DkNo2qDqJFQNHEKtcW0onpa9i9GoPy2cteZitV1F7DRHqDajrSZQCvnmfeV91EIs8CVcAL6Fn7Iz1IBNlRn01j0JZ97PGng5VwkSHW6PugWE8OomMmeg1fK6DjKMUQ5tCefrC9o0tgCjgFqCcFx4XBuo8x,f34VdcpBSt4bKC4NjsEaRrLXcE9x7AvfGbUI5t5VMxIgBnTyh9q30jmT4uidbUuGeF5LFmq4glSqDUmXOQ2T4NXMWyKyQCxJOhoowewYVniNuuaaKHpk5MuB21qItawvH5sjfPBsH9nxn5CroFljRWtTX9NnliUdFFgQIjtF1x0U8k4LCfhfc6STsqCv6afWO6aKqh6tsqZ0LjheOEPHEQwQdiwpMpoHJ5d7xA2sNZdyPEyfQ6dVEmZrjCQMEpNR,armRZ5eRaTlpXr2kgBuaMfopvIPIgbQ8FNprKdnDPBmjFA4BYnGZhVmK1t32zdh9RkyFFmgHU3F3G4DyUM9vK4W0t4QNmKB8HSylJGfYlyZonExLnusekXcHdJhlzJUkUUIqA4Cb1j6VbynhkMP1v6GTfDH1hwcUpnDo4O4bWfAU0YgisSzLEBNZYVfYKqqgrqNzC6GoZNlVxFQNAq8UznSSsB0kpriN76U2NeKJPX5TdaXpVWCjxm0MmF0jXWX5,OBMAnlRKRsMJtajk3K2TOrlywukIoBXWqeZvBV1EMOYZrIHHEkQzctbWJ35Ffwrva0TNYzX5clzMKOqu3szYyataf86f6H0mK8mIz6FuwTeLJWeaOGDQxxjlenYz9XtYXdzh6B4tiWtq4QJYc2PQGhAqHq27yLZSBRSm0NwBADaacdY5yUhEkASqcu6yNl8cecfA8xCS6irMpSPGnO5jDoxtbqf4NSclUjZZEorVy3FRPWDjTYeGKyVd4ZhYoFad,vVvKhIMlfXCPJwwPFTWybZxPisIaWjbE1UckrQJ4E2IJvfJd3FG30xD6DqjatGrz3WHnnX9COYFrTetGQbuzaKB4BI9mOmnDuBFa63uFNe6QnW2tl2f1AXCZRBr0cl9kz426AxW0Y0yPp7Sh0K4hbCZycBsQ4qzLA90TFUDDMciw03XrwnFA6QOKNiAhxarhxecf3jHO8yBCX9EuNzlHlXQuVJWymBJB6q7qTDHrK7Ue0Rb67VUQ46dYdt1SJOlK,tzlDMwNmQSKIW16SJigJaKJDivNaaIPIV7LF1UQXNEvaGqepwoqCCfRWBtqx8HjbhAgUTvEpMnjc7JNh7n2J35iaT89iiq9CDPrGKOcUtcfWTs6XZWfx7eqlDYMoS18cwTfAlTUUKaGLgbb5a4IHcTmSbjFTDqHxSOaaIhMsjH4x5tJkGWvQqMYJdqenpxqEFpPcr1K5taUEz0qKl57ARMxqZopUeszBd3BefRg9bAACw70MYKSXvlWOrlyfMgTq,ENgChatfJ5V6eKZxFYj1XjcHyZGcgw9l5hNzrtv4jEg7Yfddflf98dwsyhqUTzAH7l1qCFZP2hUweuA9BQ3skO55FkPE4op8XDNQlC7jfASreovCVz1hHgddy3WucYurE8k0jTKDM8P1cljVHkubV0zJOhdbD0u3MbJg4bmLjrYN30k2iY3uvXDIyYYb6bTWC9a7gqhOSfT0gmxWwD9JAkx5clpnPU3j6vRNSeXj6iMOZrlFM7UTudB5w7QpcWUf,ePGu28Z7RHfAubH6yUxROB154Tfova0y6MmyT4UOhA4a0cTkGPiYUvLvS7swQXOubxodUuYzYz7ekNq64gv5MWS5kPbtWMSej7uOLLIiYr6ZRisb7QxTBmdhaunNJmGoQaBzrVQEPgDwzFMBOQmB3d6TtPwYl4UJES8QVaZ7ETGRX50I8HjCC3BnnUDlS47XvNz8OToyMTZUxB9qomqsRbYRdimM2GDhCs6oW9eeBGGOU2udsS38Kq1gcN4kUOAH,gj9fQBe25ps2fSoDcaMUX1oB7Q3vy6n93BWe5qP16LXgUE7mGeNbfzWKvvBd6hDM0ub95UAV0OGIdyNFQjPwG5emUzwrUPh4UfLCzlqOGo2RhXu2vAtRd06ZCu4hy9jWrCqoDIBdF4X4sfwhOENHmY9UaJ1hXeoNUZbBjBNrIqkTOC5xmnM52jLWRiUeNUK9qckgNQo6UXZrRlEphPAwOemeGZWqeQN4H7izC02GvX2dLCcYxVBsEJ8yqUjhhW7K,Fqejr065Gm6VeZcAfTLV1zG7jlSHBzfaxsP3cU99SDMLegchY3udknc8R4cs7e5Ui6KYVdXVvbpQrvENToCLXFBQN6PrIOpT322YEBNIgti73Qr2OIt8eT2EhX1RAIliNlMYNMZD7PXPMQl8mljN6Ld7qtN2e6fwLpFh4bKePo0blIJMFDfKE0WsmdfoQrWH3ptw0X6iwkMqRXbzCq8Okwl6EEnFb3FXzYWPGpQPA3NvvQCu0PtnQIqw6ujdHHOH,iDM7TJiCgjIn69qNiqekGqlYtbyVsbhCl49pWcRUUcs6wl5P2NpK4LeVUlFRItcBzEpucpqB8gcPscaMZSXqStIhu9WCzYmITv7bPIJs5nIitE51dToMSgSkFKwAJ5rdEnkA5e2IzuDnFahVEoIAp0nGieaCz4AgynslmGEoBZibD2grgV5U6O49RUy5D2aWSfChs15sxCCjR2mO3U7lk2Z5mIT2kXG4a2ZBJokFaBywp0Oq3pRBLR8Ds7ah5MrQ,bc5OBMwNq32bCCSy0j5sYCfmBYgNMugdVc29tOq556rCw7W3qvrfr0AS3oeKJ5IeSRYlwqGujxcZNEb8nFHo2MpfHZWHIaBJi6tL1TEIEYxVGeZMB9b9bqDX0te9e7a8oVntsPjXCU5JWZ60sFyefdu9shvE5X8xP1ozJTvSgM92tbIAiXx36TwPuxe1tUwJH4PRTYxq05r8t2gBzd4VBbh8PJhVebs19TQXBaBwusl5vTTMYtOc7lssE3IwoH1w,kHVrxdt6SnZAWUMUfGzt49V40HibmZ1wkn9DWmKk8Iurty8KRuZUPitJvC2MocP7TmOMxjHcYf0OJ3qJPvz9Jdha8ONQhkAxjWDZHlp9EOHgBPHTez99h5uXsJ3YmGsRr31o2nz5ElyE9aDEJ2c0UBzhBlyV0yYbUP88v3SJkz6fjjDcEyPvPlplhhkofu2IjxjlM7GrmFsIZRpIIOkGW30UZfZ2MGyPhvZ5ar1p9DxN6ADlB8aPjkihuiGMUIh9,cGiEYARkOcSvuylKkF9X78ilpVrGmMDQ2BDbzSoOAOq1TojEe134rkZzl5gcTaBFOAaeMF9K9mmeJnOWj09Wj9PmeCWrk1eFDRdXciZ7HMLpSuIhH9SP31IYqDVG1QUcyGZ9roHWbxDj9gYdlqZrpbis2PxTi755JluaNwDBp9NRk9knOnvrViBPBjzAbp1eFC9nc7Vre37LqansgUQivtIR3nQbLE6VxsUnQFdV1bd94r5LVZjzDYARjoAiAqa1,gP5iXEFv8KCn2n59UhPMiTcZ3p6BqmpnTtlHSJJFpBtyTlVBEI1XwqgNmtEwbhE9vsdiijiBtULQQSZi4CcXqCoQf2AgV4VVqPBJQNRRyKxnx9joUCCouBVfyPaBGcWBONZvvLmwxkAXU0ZLJbhYkgcma5GJFwRXBsz1SwOI3VmevblGQP2EtIz3EzUd9KAiPosGYjd4lo2UthQaAX8bUfOdlUHwt666GqQdBGzFD93bqAl0UysdlU1wKtiZTzG5,4JwZ30BSW7SiDDNr3GDRkWzHGA7bT28wHk9w0SyUGVhGKe1Ry7bOzFnciYeJFxQzjtfcGWSkZKyR4M4JdRRRsUtAK0vzGvXal5OqIcrK1plBjSb2n1cxhn1Kc9ECrb1CpSpk272t6NKHnXamOHbeXOqSd39BgYPkog32flXDjcI795rUn3ezrW4qA2WErkntkHI4VrWGNkhojA3zzyK5t866F7pqYyIKXU9pqHjtGxubnovZM3LB9Z7uKZizDKZI,bIczFBaFA3KkN8AL6esP7eDP21OPTXLx17Yo8gLJRoo1oR3gdx3J8XisJBnkitY5195j72sqm4pkSkGvjAH7E4afBiYRwDRLy6qtzk8MzCGjoIIEPoA4xJv6mq4FBCVByu0Afsz7IBaHnsqcyFOHhWaVZhPQQpckvbj0NtaK2tIHN8WoVeMopAfEmS95XQOLMXFZOppYIzEhZUDPjVOYzMVX21vcqlj0kbKaRMT1edsrjY2f12BCa0XtGVvqERSs,DdY5Jy8pKoRNPcJ2eNm42izItiZYTdFhC0A4J0jvTYYNGvbpnDsMF7d8xk54kcEqGcH2R0gydHHCGx2iLPtzqVw5IXy8VSNDNVVix3OZ9mSKjwO8FT5Hdxqu4EOnetZ4B3nxch0kQLe4cxjk8Bu3RKDkdPJKtc1XtgyNHjtXAK3v4O7ZHamgVxW25wokFJHZmp1F6PhK4D8bfw98mIIpSS6nCJOUPwTNOo0lW4kL3ak0P9BV8NdMyf2dPrXEVRrl,3N2RolqvCDXkXwzicRSFmB0Djy99sV4i9imNd3c5BXb3fDMgQbVBQZXnW0o511GHwvCKSeDnGS5hNEa6lvnWeflFoQAcWmX8uYmWVVzchSQlfdBNOHMNdFEI9tv3xituIjvtiad8VwvKNjkd0CJ9KiT6b7lwIAn5Kv4zOvXJST2qv0fYB3L5AxQen3BRnP71drsQERu07lDoVOewAhLxFd2t4y9DrnrTS7oRbEwTS8Ifh5Xi4RXI4O1BHqtZvpG5,eQDlbaAYUSs7UNxszZiUw97S66VLYkpjnvLv1Zqt9auAnLkeOmeSKZ7aDDc653PTrcbxPpk1iIpgZslrUj4ZzvfxJYf49WktIPScYjZeiwOK1ptY8UVFRNV67N7SaWG7Bs9fYuEUCRJRXXqDkcimkihd0B6OLSMY30OPhHVvIzk6pjx2tl4z2m1eactmCZDUXR2LjKzQLXRhfT0oZUPpYTtfSFvH7jCoJFQvpZG6gWDRUypL7FFkbDsuT4EbjpHI,smB0pE0n0RnbR6Werzk4ccBBAQUeuYwa8uCCTVlB0d4Prz6XkLpbaJCUgfaRbnzfoFXfj9PYsJcoDTg9tYoSDJZM32vUV4sKIopDJk0GtzLdlqFRxdMKWIrhVehpHyYYfNKCUJLCFDDQ7QtfOLk8IkqLLXGE5PlfqeolJHutD6nU2ZL4iAzn4qcIpAGRMFSxQRWU6oo3ABtAm6BzuCCGUnJ40xtwM354A6nnfpSiTHibrVBB2yfevevdH4XlOSKQ,Z5d3GUKRDsMujTfNVnkfnLL7tN4n4B65aGeftq9JCjlPPdLyIi5u39xHPgBZe859cZMxheIrhaidPk3xz9W2OdFylXV9hURevn2gDZJEftJ2F7Ek3Haxnbv4KIq33cOBJ25JDPLCAeLuPWAxlRI8wrKj9WIyOuyKjoBcJayR8QjONlyjTjzu0wgPs2k50430l8g01v1cWsEM56Zr6aAirpHLJJZLpAHnitpKoow5zxpAj6rwAW6fJxlDBoyozzQE,sVIiVFuU2rdjSHAKCrhfhUDrJhRnBgYrNba64DEASFYnQlrE2BuIvaKYLjAwilVXMRUB3rdYPtICIegHmLnGXJDTA0ho3bqjEFg0bJH31zIOdZDobYEq5fNbMZ5SqmrOTun0ziIkEHnOc4ams90se5AnxDmsixooPj89CokhrEEXWOstWzg1NS2BpWWCGpa4AEfekdaxxKI5T9DH85eQgMx4MkbUiPVbt82OfJMQFSsoJsVTrL8xn2UujtO8J1AT,wufearjAjHuup7UAWuvSmr5AcZztr0Xa2E3KEB1L3htd30u1bQYRuuzh18ZqKsXdwyYUUXWVofmiFO2YPtYW9iQU3lET2nNQ2xmuMs78QqgE6eFDiCMpg6UHA1Tz6sXbN3Uv9YswOkjpBfPC7fvjBosalXhb0qB3f2DxIuAjt4aPcHaVfQDIyNgSBcBwV19ZZHCjoa5Q2afRdAJNuVmWlRCBj4o40r60wqDKIfQqHlzihY0vFKIktKari7VwZL7E,AlVBf8kNUeAkHHcGeFmQQwMglUGyl6v8aCIKEKHp8MgkFvYLoiu0m5h86Kna6yFI23jRagrUhbgfwTqvJGHQyqntUkFug0Xg6Pyf4fwOaARhaVWL1WZ3hQ99aSQChPJtWCJKBr5ArePpvZC6oYsqLsxqlVs0szj2kVRr6KgpfiuJv3as9FbpbNKVdphdY8eftW0geBCLgFRiUpoxVFDUrXlnXmypi29KEUUjQsSsNN8E7c7XuGhpsfwwcNIm5kcF,s2tR3PCfE6HSXm60ax64MN45lidkGNOJviFfLl55CUnYu8ZsjOtKO8bYAm1D3Nm36Cpm3wNH9blyEJbfWlwwCDFtJEz3Tpvw3I5wDtJxz0mQayAXgFmr9hEb3GXLYD4bd5PSMfWE5UpsXk0Q5AnD4voKCprfMy8tEIIdOQRWJXLerBP8LGYymk8VupgJGDi1aaHB5H846KzByCRTCIeioWSvDKxmUaYkOXOVWwuHwNiRdC25S3llxRw5ynoSEd1f,tLJqtM7fecmMXjiCy2Svno8Zo0vhoRVb7oPUeEySWRZ2nGaMNXJ9VvvJnZMM4fDQVC1caXUjWW0wdGjX1NyWcumB5RISPE5WSLQjNlGBj3gqdW3VVpXL3bQecefOPswjAMZmHIWh28LdDbabRDx98ZrGteCiTDKgTmhX19Y0udI4TcmxJTvQJIrbHv2RgKFf1WspQZuvUlGZOeOvp28vNmrFugTlAzt6ebhyzBfZbR1KI9W3CrX8K9NVdW1tma8w,8f6jgzRhGFbHoisr5ioOqmpFeAVppKaj9d75kXgTXO941wRFYEiRypa7oC2QwJs5LltCp8FRkZKgPcl0qObWQVzCyvnHzQ80mGG0H5qpfuyKeGh4u0TYUzCwFCC2yluupaIEYcJLKLwNYBYuQOvc9iR14YEsqyRIq6JhxgNJ4qXW5vsatc4wHxTW3Fpy9V9CM1NyXvI7wpJTe60JkZM62Q1KQGJdjrZaQry1QtralqIJPBayE1GhrDCLlfrEZ89t,keTp2v6tECY1qvCuHhCzC7uB2MdwsKxAinm7Bz57jHOQCrRWJpupTegXDT7AcETtkhvDgZKECeA4Z59VgdnmLKDJETud895wP4MPLGHhO4qY1yrDcHn0EBMHfyZGtp2uc5UCN6IqAxxPtnfev3auCPWV1nSroSmARBrxTpEssH2Vb6iA3smuiFKuHNnuW2adkG5Uk50J7JRFdgnRBvQSJKNNWiwPer6cc825yIT0ubdDziKjAIFPY0mJho9FhxgR,E5EL0Ybj7Vn2fGqoVmBG9wiNXQ7DWqx6PLwdT8sYOj4qzMzVecmn6WPbcPUrS4kqo0XjO7o3t1xsK4KE1fuoT546F0njWzarw9MnlrU7eMXMI0tt3BH9NG3ZZ6mpDk7ztctcaVzN0Ks8C6CI6Vn8KVdviImY6Urmtd1h6RJodPZhhTT7VfmwlGDeTprsfhhBAs5Hqfx4D5qcGP80b46ChzT6JbLFdgdB29jVJ0w2S5QhALN8tAKU9NKVK7FbCVSf,Eb4d7HQujRmB7rOpWzB93FWFA4mUNdjK1YqOivgXQ1IbnqvvVg9NK9kAPCVTMmHFjDXuLU7QmrrU74r8xOj3ufnAGDVifIuwm63IUTYggjSrlhahlPeLpSQrCJ1ophFZgETQ9IA5czhbcOY6QubdE4vKdMN9gBp0frbDz2lbY8wcqRNlZ4f7J8rOpOJrf0uu6mDIxtTlkbOUCL7PmJTP80L7j1k8ZgKdgDn0rzvhG7Qn7rMO6QuGbKwAB6cL29tR,M51LXG6MeRIBzKJ2hKqX3lVFGrty4IHMRosxmeWvHs9bUdtVcSx3gpHUCJNNA0uwrBQBkOGxBVeVgVGBUtvV7583aj2NPINv8F84IPG8SjFxscHkkFxelRhS3npCqqV7VDKaRHpebUkFfa5FFghstsiE7Fh9kmd2DqY2pgQ4UsgSjbm8oDBfNwDpeBa9teZcSjbZTmL09yDlsdtV2YjzR88bkDTrbFZE93aug99HprXRTRQlneJxU9UG5xp3eG,5O5rlHslIG3yG3YSSOZShAbGj000PB5Wf6y7EXwbtckB9hAr0sGtG1WLUQvS9wCBMycPzThY60ojvPw0ra6YVAiw4TJKzckCSycWadTjFIK0AVwb1rH5W0VzhQKnezt5C5mzAn8F6Wi9rfAj2i2p5JpWmjNxiaxvVX0qCZ6qcGIK3Tr8NwTyIMpMwEg6tM854kUzoIrRs691s3NhYV1O2CgkA0twOSsdx06rQdkg3AqgRufbzJVUx69iIpnsrDfh,n0Q7AZWnkmKq3Ev2iV2gaxXb4MLHVX0OBa6698OMZIt8w1zUm8ACXUjXBK65PXltJowNU9493LsGf0XksyLTxbknpdVPU5IvagUrBTWfTH2DDFevHas0cY75q3vKkkxtNM926gOJbCfrJAqOGotOYJ5WQXIWxUPhKtkSKH99Lv3wCao4iaHzenFmBH7hivVV3nv9NgZQNUEJRY8MmzxmDBxruC4WDZzeNgYzgCMKtqP5F5WGmv6aFt4Rho1aYyiH,LkhLon5uBfXDorPqA9lKvhqh9i1AgLGesZmiQ75434JvrxrcR7NRo50lEFiE5OJl6OwADiPpRoQKzfDSfcI1659cbY6LtihUi4j8P6ZtZIOwybgdsD4ZbS0oXDg9STIAMpDiIuRbccPb9YXMFrQfLwgpjon2sRS5L3cKVA8nZmkcgZpE2WCqbhb7hSjDi5H3xPekdQH1lpCgHoVs9BfHB9rUTlTIY1ofSsPyXpBWm39UzSU6cLeKD3gpcO99YrEz,l2I0rxMKAr6tWUHvWjC5zQY8IkronIzlNdnPlREPbftHi1poVeKpS4INT0vSSpuggRaIbmTzFTbXsZ1in7yCf1qgGy8t7WGCCa7fjYOe4EMdHs92e1zqzsaT01dvkR0Xd6HEEpdZmKrb9hQ2NmpC4Ql6SyukIvTyBrkb52aiubfGYmRY3k7JPYrEBvZp9gqvQfLwdSX8RMekJEWs5ISZX4Ld6Jmu4jX8d1hiSGVHBv0MRvtaxpwMXnGrkCBNtNee,uLf1W4htbKZnpJQlLofx2P97nmA8ar66jG9RbbZwvUqzzbcsXyz4JAAMx6oKPvcgtwgFeqG3t71rx5dMEcb8fd49CJVdvJFiqtDm9wy74XgUZFd13tfUtZuvzBTGfWsgnXOahCLnA3JFxM2fesLhhw87rDWs61FBVaNzmZjmUlZKkkPJdwLx7k4jmrCx1shq3Tq0nOjF3JYx2rt5JBEfiJO3fH0ZBqxoSkLhpmrCvbjo1LL9fO39jChx8tVp5PjU9CAKepnzyr8sPZCyuEEc6qZq7bp5tUQqRdpwhRyKKeB5YZ9LoSCD76MQHwxnP7WSS2LaxdrjeVogbBQjw3a2XKtCdG1CUwHDqxHcUzzYsjFZXznGdM3iotRNMLqvJto8xMwyU2bub4Mm3GfAV7tObrA9R56lgCBsinFcYSb36uXOTCbXDirNDlV9jEXtM2yKbAZAoCJjsVR26OjjiY6PhD3kIobwvJGEsAAF5XTQoSwLWqNn3nRXqv2iBTJ0PmS7,w2alFm7V4ZeuR0raPnyJ06XwodK5VbvjcDuFcRGmCP2H1iqVs29CkiRljfJcMF0ijQPs0q0echAyJ1Rrw16FJVheqTxXfGJyTSADQC1WevxPwm3ZUjqCrzuWCTK0AbxquKbnpiS1mHDTJhSDNqwCYCsMA8gmodOWAeAYT28i6QJPXVrrRJeFIvwcaDZAnKwGZnN2BwN9whfOFoorcfeuNAq7S0skuF5C8uFXiGjBHUxwYWNHLwm8MtnVIDw6ge0N,JnC5G6HIj31YgjnNPP6EzZEqmoSWqH9y0BQvT0vmOpaqZrDZLkxkRBZAM8HQ2uz9rjdN5vQtqDrFXlr7egJejAhHDVwjKlf9Za8M2SDknHbYMgzzx2xB0syvy69MHmVXlaXdMAASUhtCJnY9h5whTliPTsSmnthSWikBdnU85xNEtPd4HO1lbGubK54zwaqxYpQ1iLuRjAQNntdVcGxuDhKlOx6UNswsdBNDa1DNRaoxCiuSXJqTCnDbRjcdEHLF,j5q5JgVK9A4wukpfsLDvuMJQd5vPvZiu1b6ewS1igNkwv03XAXtSqWYotuVguewwJkFgipDyC3v9eDK4r3xtw31k4tRA39shGdzIaHbf0ZrNkijOfgNXFc7hck9UkIXVFu2iNcG2Efl0ErQ0lD5BBdZpvInunLMiepX5S3dM6AXbhIws1ogiXTAUzYRuMYCdDfEoOftVLMk11rnaIclSpeEWwvOB4UQaNPLCZVVGqT3wyapZiy3a9iNyLQgKYQYX,YGMxM2PvYcklCpTlcRp4UbwZ9GQFv9T4kB6Jd5fnq9PsUc9Yh2MXKcXRDbak20X65hh3FYuqpBrqsCwMzd2sTl9bdReJrnmUa4DDYCayQl8YpHIc5mFjxv7acNzrUFhNKrJxlzUVe1ceQkUJwmGx1CIiXMGNbNt1gWMqkW1rPggOqwwXgIxySwFpNjMsrph1YaZEbgMIhhRJLXsgzKrQxnDq3ui7i7mhaLiilr8XFBjaErCyxA187J7PVCrqFrVj,AnLNFVFgQruoWXZQPbdBpa0OwgFNhwuQIQatnG6sQFIUyNaC6NX7zMNS9VmaC5299A2fKC9jO6UnDLEGLgc11iO4uwsSvNUjSSfJ27wQHnIvfFIMdSEhPY1LvOFoftCdwgfYtxpbGPococgk54gVKCBPuXpFUaVQTmeMUCcPWqeXIjswtAgYCxu3YEmDluOnzBRlGxN23lkfLBFqw3tjabFodiJIodbUenxuQIJTM4CVmml4h8Q2P3PPUgfNLdqL,iw6uHztAHfcWSxbD8Y1vF4J8thpe8fGajCNeouwugj9faQcTFGzTsXrTuaNNtBBUXJtJAo1TeyHhJM6wZHAQQBRbeNI5ZC5bWSRlgzg5VM1YICbCYvjEpVpKXiytcXBnlwFbtEhwdUM6kMEf4tnHhlw2RZy54mloOZ5fyhEiWDElc32D6RAP1LKl1j27Rx8NGud1YDAXkOdYyaoXNi2azR1tOEjb2SyKraheaz11OnLUong9XIggzi5TR3afhmIH,XKNRcU0NEwc0paQmbhzwlEXNQOEiDj28H0irqqID9cPj8mF8xZKr3T279P56qhlqmB2yfyyzLiIrDtlE1XCJXFZ8uwDZo3xZYLG01D0giGmJy5pYG5b8Rgh49WHHO9SfIEHes9XXMElYlzp1n71Tx6WxM9DsVf0iPaTxRbVRBrlurDLlEPgfYF3BmF2NIj2srdIkPrBKs2f1DknFpVtzyauXgMbjHTf7Z1iiyUYHVmGNKBy5Rhgd57uRavMSH6Rt,xPKZmTkSpfdRzh3TcjwEjjD0z1yC8Mb1GruRfCtjbPHrdD252UdXwLi4i6ilW0qXjL2rJeVMQFEPNV1mTWWFaK03JZsZTt0xGH8oAbfoAtRLGMBIWTTwyxjTlwQsXOHPA57svfOMURSurXjpeR5ykUQyAL2BRs0IOs9AIktyRrAY9R1Ya27U1Cvw8aiEm0hrLaZo7jEhr5KtS8dgTjXWmehEabCZLTlucoOrio24MP1RmBKGJavcoVG0nemFIwcI,NSvw8OyRPXYa9Z62nG26Rgv02dDmYbcF36Hu6NXnxxY3B8VgvnODde5iO86HRaOdMCd9C1yLUxIEzwqarhuZjhs9SWeGJYFuNAZ5Sx0E5Xnwdw5bicmx4yqzdapjIAZTMjV2DD2Xf9c7jOWtcXtC9IoCBunBq04uNBmF0qCoYUHfD3uEMRGn3GOmEJv6qNSn6XQ14AYA1S3CqBb0PQS2PhA9nXI69b1uSQjZQvHHmmuYLfNdWJ5qDqotXxLuDzhW,23fohaTv1QbHaw1is16nLwK1FwM7kyGiXEInZ8SHKq5X129vf2nbF3xmL8L4p3Me79y6RXnvLYIhY8fN0omj1Y6FOc2Pqh2Q5OWGUtTL8XS8H1adMViuLJqv14WP4mDf4Go84tdlVVFaBqZGvpsG77PuXqjhMjUZfeOFrbNBGzFRO3HcKPA1mE3DuW37IIbs4GojhcTDVSlln6NmhLfocqVEezXwVLYIxdjI7Tj80kaPvESOnC05gBuQTrq07uqn,rno4DZtFWaG6JwygqSmFUebTyaOVeNWICnD3Oekzlq4M1wCM9KLZpZ8G0VaW0GXNXhDgMBftfB8qKMoo'
2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [3, 5, 8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cli,ent disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server received all data: 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,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
,[ThaliCore] VirtualSocket.closeStreams() vsID:8
,ZmXVzsxFhZVFzuryds80LTJaiIorWakNysaH9jVWHSDQ9rVeTKo9wrmFoAe2cMk0Eqs8sBimdqn7qDitUNPZQjwfoV37gJvDMnf1dPmOc8BEnEZxd9QlVsyecwU640y9PDMXMjMyWaaPyp3h4DHtcKIVUAEG3UptTUvvz8HfmsqDa2ivv9tHnMjr74VS7q5wIUYkDZ6NN3WABc1Efaw3QxqOnfCbvWqyJSPpIPHiUSpptBFqMCUXmpQqbrxyPrf3,7TIgW3EwG9TnzLKxcy3di7akbDtMJQLHbZI9XjrZGwSCgy6x1HoslBFh24MIP8BlDUQITjxB4ylr0h6ySjoTkkWKy6mbl4IlxZFOoAaRem45TQJtggiEWbKhfYpanOizolXBGuGZoie1PIMp2kiUaIrLdKiwk6mmGoDnPXj88nRsnvWhRjZKgBAILbOE7xFmfduZwGp4Qman5tla4WtVh13FvWsk020OwtpSSSlSPfIU5kj7K8SCUI9tCV0vEs2m,9Ur8IsZAHOX05Y7AHjjufJRWiNq96heh7TwJrsibo9eVkw2CYji7zP8TtDel8Kaa05fzcb0NEnPt3wUYuUxlIyBcgjvBwgUZzGbUdM6EJreUCO7YJFTnMYT3ah9SWhxGSdw1j48c6r6oUDNBkUsZlmUgM8GWADg71hpRBhSIJU5KmlAaHTAlu6ZtrLRXD0vg9zAB56xBLvaA17WNTxIg26Opwq8NDOQwMtwWcn8y2VmBOv4ehGDwWzE8I4dIr9IC,xxuDr25FEGVc54FKjh9KhPi0IwccR1DP5AN7DS7l945IqlmaOFyJ4Ehqm2Lz8MxYx8lr2ttnvuEVFW1T5c2Yi1cmB1xiXeU2Rb1Cj7QcWXwj7pam32lY0NexU8KvIxbUetgFQ8X8WEkDGU9EXJruAeb9MWlq6myGXzay5DYQunHOMZpiHKXsuMenimj1nu4XWo6L1qrNwTbwLJvoIZa9ck3rC4Pnc9p4qmTVZ4L9o89OefL2YQtHcRj4haRXZo8Q,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [3, 5, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,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'
2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-08-24 14:50:01 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [3, 5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DD12190F-C11B-4D3D-90CA-E076C0040F6F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:18D49381-D1C1-4D8C-84B7-C71E493F7B6B
,2017-08-24 14:50:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:DD12190F-C11B-4D3D-90CA-E076C0040F6F
2017-08-24 14:50:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:,50:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [3]
[ThaliCore] BrowserManager.disconnect peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.st,opListeningForConnectionsAndDisconnectClients() port:63278
[ThaliCore] Session.disconnect() peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1A2F523B-551F-43F6-8F63-E9BA6B74AA01:0
,[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:88F25900-E82C-4806-BEBE-C7A0F07CDFEA
,2017-08-24 14:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:50:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:118523FF-7B2E-4F71-8768-9A523E661A64
,[ThaliCore] Browser.startListening
,2017-08-24 14:50:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:50:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:50:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
2017-08-24 14:50:13 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"49113C2E-45AB-4903-A759-BC5216FA0D18","generation":0}'
2017-08-24 14:50:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 49113C2E-45AB-4903-A759-BC5216FA0D18, (syncValue: 4a0O1dwjL64K0VaglqKFvFWRjJga1ns2)'
2017-08-24 14:50:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216F,A0D18", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"81E2C700-B307-4017-AC4A-E1CFD3A79A7E","generation":0}'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88F25900-E82C-4806-BEBE-C7A0F07CDFEA:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
2017-08-24 14:50:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EAE4AA8F-4F52-4E41-A600-55B6A1A4497A","generation":0}'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:50:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "49113C2E-45AB-4903-A759-BC5216FA0D18", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:49113C2E,-45AB-4903-A759-BC5216FA0D18 error: max retries exceeded
2017-08-24 14:50:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4a0O1dwjL64K0VaglqKFvFWRjJga1ns2","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4a0O1dwjL64K0VaglqKFvFWRjJga1ns2', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:50:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 81E2C700-B307-4017-AC4A-E1CFD3A79A7E (syncValue: brHqMQT,011jclViY19ihnL8cDlSjO2YS)'
2017-08-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:81E2C700-B307,-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test,!'
,2017-08-24 14:50:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:49113C2E-45AB-4903-A759-BC5216FA0D18:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2F36D5E0-305A-4C32-A824-DE87C37D328E
[ThaliCore] Advertiser: session connected Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2F36D5E0-305A-4C32-A824-DE87C37D328E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "81E2C700-B307-4017-AC4A-E1CFD3A79A7E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63299
2017-08-24 14:50:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"brHqMQT011jclViY19ihnL8cDlSjO2YS",,"error":null,"portNumber":63299}'
2017-08-24 14:50:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'brHqMQT011jclViY19ihnL8cDlSjO2YS', error: 'null', listeningPort: '63299''
,Connecting to the localhost:63299
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 10]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:63299
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [3]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 99 got the same data back
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2F36D5E0-305A-4C32-A824-DE87C37D328E
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F36D5E0-305A-4C32-A824-DE87C37D328E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2F36D5E0-305A-4C32-A824-DE87C37D328E
,[ThaliCore] Session.startOutputStream(with:) peer:2F36D5E0-305A-4C32-A824-DE87C37D328E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 11]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-08-24 14:50:28 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeS,treams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
,[ThaliCore] VirtualSocket.deinit vsID:11 [3]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F
[ThaliCore] Advertiser: session connected Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F
,[ThaliCore] Session.session(_:peer:didChange:) peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F
[ThaliCore] Session.startOutputStream(with:) peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [3, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-08-24 14:50:37 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-08-24 14:50:37 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-08-24 14:50:37 - DEBUG testThaliMobileNative: 'Server sends data bac,k to client (20 bytes): '
2017-08-24 14:50:37 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-08-24 14:50:37 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting,:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [3]
,[ThaliCore] Session.session(_:peer:didChange:) peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F
[ThaliCore] Advert,iserRelay.deinit
,2017-08-24 14:50:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 ,14:50:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:88F25900-E82C-4806-BEBE-C,7A0F07CDFEA
2017-08-24 14:50:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:50:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63299
[ThaliCore] Session.disconnect() peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F36D5E0-305A-4C32-A824-DE87C37D328E state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "88F25900-E82C-4806-BEBE-C7A0F07CDFEA", generation: 0)
,[ThaliCore] Session.deinit peer:81E2C700-B307-4017-AC4A-E1CFD3A79A7E:0
[ThaliCore] Session.deinit peer:91F882EE-9CC4-477C-B549-B5B6C6F9DC3F
,[ThaliCore] BrowserRelay.deinit
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:15347059-D945-4F19-8F57-C4DCE18EF619
,2017-08-24 14:50:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:50:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:50:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FDC19618-EFD0-4DBD-9975-A0CE67660870
,[ThaliCore] Browser.startListening
,2017-08-24 14:50:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:50:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-08-24 14:50:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EAE4AA8F-4F52-4E41-A600-55B6A1A449,7A","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EAE4AA8F-4F52-4E41-A600-55B6A1A4497A (syncValue: y2pIW5RWqGhD3Lcr3yEjBea8CkYEpXAX)'
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3","generation":0}'
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D857E22-1043-4D59-866C-EE82BF5CE43B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D857E22-1043-4D59-866C-EE82BF5CE43B", generation: 0)
2017-08-24 14:50:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D857E22-1043-4D59-866C-EE82BF5CE43B","generation":0}'
2017-08-24 14:50:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:50:41 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:50:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15347059-D945-4F19-8F57-C4DCE18EF619:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA,E4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,AE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA,E4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,AE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA,E4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,AE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EA,E4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "EAE4AA8F-4F52-4E41-A600-55B6A1A4497A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:EAE4AA8F,-4F52-4E41-A600-55B6A1A4497A error: max retries exceeded
,2017-08-24 14:50:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"y2pIW5RWqGhD3Lcr3yEjBea8CkYEpXAX","error":"Connection could not be established","portNumber":null}'
,2017-08-24 14:50:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'y2pIW5RWqGhD3Lcr3yEjBea8CkYEpXAX', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:50:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-24 14:50:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3 (syncValue: Kjv4WHqc277VQDfXvFpwRS0BdbQ3Rq9L)'
,2017-08-24 14:50:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:50:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:50:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:EAE4AA8F-4F52-4E41-A600-55B6A1A4497A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63316
2017-08-24 14:50:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Kjv4WHqc277VQDfXvFpwRS0BdbQ3Rq9L",,"error":null,"portNumber":63316}'
2017-08-24 14:50:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Kjv4WHqc277VQDfXvFpwRS0BdbQ3Rq9L', error: 'null', listeningPort: '63316''
,Connecting to the localhost:63316
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
,Connected to the localhost:63316
,2017-08-24 14:50:53 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-08-24 14:50:53 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [3, 13]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EE55610F-A9BD-432B-9147-16B5D83755A8
[ThaliCore] Advertiser: session connected Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EE55610F-A9BD-432B-9147-16B5D83755A8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EE55610F-A9BD-432B-9147-16B5D83755A8
,[ThaliCore] Session.session(_:peer:didChange:) peer:EE55610F-A9BD-432B-9147-16B5D83755A8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EE55610F-A9BD-432B-9147-16B5D83755A8
[ThaliCore] Session.startOutputStream(with:) peer:EE55610F-A9BD-432B-9147-16B5D83755A8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [3, 13, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (4522 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received (19617 bytes):'
,2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-08-24 14:51:03 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-08-24 14:51:04 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [3, 13]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [3]
,ok 102 got the same data back
,# teardown
,2017-08-24 14:51:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 ,14:51:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:15347059-D945-4F19-8F57-C,4DCE18EF619
,2017-08-24 14:51:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63316
[ThaliCore] Session.disconnect() p,eer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EE55610F-A9BD-432B-9147-16B5D83755A8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "15347059-D945-4F19-8F57-C4DCE18EF619", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:EE55610F-A9BD-432B-9147-16B5D83755A8
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:EE55610F-A9BD-432B-9147-16B5D83755A8
[ThaliCore] Session.deinit peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:910737AF-607C-4BAE-8B6A-9879DE93456F
,[ThaliCore] Browser.startListening
,2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:51:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:51:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:69330754-D171-4001-A667-D359FA9BCE44
,2017-08-24 14:51:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:51:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:51:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
2017-08-24 14:51:10 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3","generation":0}]'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3","generation":0}'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
2017-08-24 14:51:10 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4DED5FE0-F5D2-4C10-B30B-CB988DB7345D","generation":0}]'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4DED5FE0-F5D2-4C10-B30B-CB988DB7345D","generation":0}'
2017-08-24 14:51:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69330754-D171-4001-A667-D359FA9BCE44:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69330754-D171-4001-A667-D359FA9BCE44", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3", generation: 0)
2017-08-24 14:51:13 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3","generation":0}]'
2017-08-24 14:51:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"CD334B3A-D5C0-45F0-A8A6-21AEF889A0F3","generation":0}'
2017-08-24 14:51:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:69330754-D171-4001-A667-D359FA9BCE44
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:17071889-7DB6-4709-B8B8-3BAA9EE16EF7
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "63A979A3-B7DE-4B32-99A6-F1A1805FFD03", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:63A979A3-,B7DE-4B32-99A6-F1A1805FFD03
,ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopA,dvertising() peerID:63A979A3-B7DE-4B32-99A6-F1A1805FFD03
,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
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
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 114 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-08-24 14:51:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-24 14:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-08-24 14:51:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-08-24 14:51:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-08-24 14:51:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-08-24 14:51:18 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-08-24 14:51:18 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
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
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7181ea86-2384-4b70-bc7d-fb0f27be4c62 error: startListeningNotActive
,2017-08-24 14:51:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"JRlCxQZzWO3RVDkjPIBFotvHrpPkvvqC","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:712ED2F0-CBD9-4043-AEB6-190712B9FB25
[ThaliCore] Browser.startListening
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sI8Wc8FtR2zugdupz5npAagCU9ekdNvI","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
ok 135 Got right error
,ok 136 listeningPort is null
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
,# multiConnect properly fails on legal but non-existent peerID
,2017-08-24 14:51:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A71CF633-8789-48FE-ABED-D6A397CCB023
,[ThaliCore] Browser.startListening
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
2017-08-24 14:51:19 - INFO th,aliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:51:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,# teardown
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4DED5FE0-F5D2-4C10-B30B-CB988DB7345D","generation":0}]'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4DED5FE0-F5D2-4C10-B30B-CB988DB7345D","generation":0}'
,2017-08-24 14:51:19 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
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
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
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
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:437364b6-8281-400e-959f-ceaddfeb9d03
,ok 140 No error
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
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E9508C9A-F8A7-485A-9C73-CD057AF54A08
,2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3B95A870-C139-49B2-BA74-6A9E5FA32D33
[ThaliCore] Browser.startListening
2017-08-24 14:51:20 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:51:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
2017-08-24 14:51:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4DED5FE0-F5D2-4C10-B30B-CB988DB7345D","generation":0}'
2017-08-24 14:51:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4DED5FE0-F5D2-4C10-B30B-CB988DB7345D, (syncValue: 4htOMwXCTqdYYsf3jaVsGA7yzIUHyqIY)'
2017-08-24 14:51:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB,7345D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9508C9A-F8A7-485A-9C73-CD057AF54A08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
2017-08-24 14:51:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3B568BCD-8A56-4957-ABDA-851A732D225F","generation":0}'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:22 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:88D2FFB7-883E-4729-94D5-CE3958DDC824:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "88D2FFB7-883E-4729-94D5-CE3958DDC824", generation: 0)
2017-08-24 14:51:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"88D2FFB7-883E-4729-94D5-CE3958DDC824","generation":0}'
2017-08-24 14:51:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:22 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
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
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E6DD4367-361E-40BA-8187-4C0853AC3A1D
[ThaliCore] Advertiser: session connected Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E6DD4367-361E-40BA-8187-4C0853AC3A1D state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4D,ED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4DED5FE0-F5D2-4C10-B30B-CB988DB7345D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:51:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4htOMwXCTqdYYsf3jaVsGA7yzIUHyqIY","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:51:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4htOMwXCTqdYYsf3jaVsGA7yzIUHyqIY', error: 'Peer is unavailable', listeningPort: '%s''
2017-08-24 14:51:29 - ERROR thaliMobileNativeTestUti,ls: 'Fatal connect error: 'Peer is unavailable''
,2017-08-24 14:51:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3B568BCD-8A56-4957-ABDA-851A732D225F (syncValue: PhR9fNfm2IhEOko8Q3Gy4xgFXBNyl3hE)'
2017-08-24 14:51:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3B56,8BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] ,TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:51:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4DED5FE0-F5D2-4C10-B30B-CB988DB7345D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A8B0E150-EEBF-49C8-9A56-202C30D74E0D
[ThaliCore] Advertiser: session connected Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A8B0E150-EEBF-49C8-9A56-202C30D74E0D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E6DD4367-361E-40BA-8187-4C0853AC3A1D
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6DD4367-361E-40BA-8187-4C0853AC3A1D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E6DD4367-361E-40BA-8187-4C0853AC3A1D
[ThaliCore] Session.startOutputStream(with:) peer:E6DD4367-361E-40BA-8187-4C0853AC3A1D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [3, 15]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63332
,2017-08-24 14:51:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PhR9fNfm2IhEOko8Q3Gy4xgFXBNyl3hE","error":null,"portNumber":63332}'
,2017-08-24 14:51:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'PhR9fNfm2IhEOko8Q3Gy4xgFXBNyl3hE', error: 'null', listeningPort: '63332''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0) found active relay
2017-08-24 14:51:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rTY3cStgOZankK7Gfd8fMJh6qy9EINxt","error":null,"portNumber":63332}'
ok 144 No error
,ok 145 Ports equal
ok 146 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0) found active relay
2017-08-24 14:51:32 - DEBUG thaliMobileNativ,eWrapper: 'multiConnectResolved: {"syncValue":"f79YleiHRZIW3w4hFQRJ8RzO51izDrIy","error":null,"portNumber":63332}'
ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [3, 15, 16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A8B0E150-EEBF-49C8-9A56-202C30D74E0D
,[ThaliCore] Session.session(_:peer:didChange:) peer:A8B0E150-EEBF-49C8-9A56-202C30D74E0D state: connecting -> connected
,2017-08-24 14:51:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSoc,ketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Advertiser.stopAdvertising() peerID:E9508C9A-F8A7-485A-9C73-CD057AF54A08
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:51:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliC,ore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [3, 16]
,[ThaliCore] BrowserManager.disconnect peer:3B568BCD-8A56-4957-ABDA-851A732D225F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63332
[ThaliCore] VirtualSocket.closeStr,eams() vsID:16
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] Session.disconnect() peer:3B568BCD-8A56-4957-,ABDA-851A732D225F:0
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:16 [3]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:A8B0E150-EEBF-49C8-9A56-202C30D74E0D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A8B0E150-EEBF-49C8-9A56-202C30D74E0D
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:A8B0E150-EEBF-49C8-9A56-202C30D74E0D
,[ThaliCore] Session.session(_:peer:didChange:) peer:E6DD4367-361E-40BA-8187-4C0853AC3A1D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E9508C9A-F8A7-485A-9C73-CD057AF54A08", generation: 0)
,# initial peer discovery
,2017-08-24 14:51:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:36 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-08-24 14:51:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:51:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:51:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:51:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-08-24 14:51:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:37 - DEBUG createNativeListener: 'listening 63335'
,ok 149 Should throw
,# teardown
,2017-08-24 14:51:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'listening 63337'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-08-24 14:51:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:38 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:38 - DEBUG createNativeListener: 'listening 63340'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-08-24 14:51:38 - DEBUG createNativeListener: 'listening 63344'
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
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'listening 63349'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:39 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-08-24 14:51:39, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-08-24 14:51:39 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:40 - DEBUG createNativeListener: 'listening 63353'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:40 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-08-24 14:51:40 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:40 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'listening 63357'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - close'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'listening 63361'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'Native Server - close'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:41 - DEBUG createNativeListener: 'listening 63365'
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
,2017-08-24 14:51:42 - DEBUG createNativeListener: 'listening 63417'
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
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'listening 63421'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-08-24 14:51:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:43 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:44 - DEBUG createNativeListener: 'listening 63424'
ok 196 port must be in range
,# teardown
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Creating Native Server'
2017-08-24 14:51:44 - DEBUG createNativeListener: 'listening 63425'
ok 197 second start should return same port
,# teardown
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Creating Native Server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'listening 63427'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-08-24 14:51:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:51:44 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-08-24 14:51:44 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-08-24 14:51:44 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-08-24 14:51:44 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 63429
,ok 207 should be equal
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B3AA7804-57E2-44E7-AC1A-8164EB411284
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:51:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:35D949A9-B989-4BC6-8E29-BBF5E60823FB
[ThaliCore] Browser.startListening
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:51:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:51:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3B568BCD-8A56-4957-ABDA-851A732D225F","generation":0}'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3B568BCD-8A56-4957-ABDA-851A732D225F (syncValue: dV1P3EPwOfAMAogFtJAHxhuVSxg0ctb9)'
,2017-08-24 14:51:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3AA7804-57E2-44E7-AC1A-8164EB411284:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
2017-08-24 14:51:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD09023D-741D-467A-939B-EE587D2D88D6","generation":0}'
2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:46 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3CB5059A-D11F-4536-8716-32BED6C97CD6","generation":0}'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:51:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3B,568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3B568BCD-8A56-4957-ABDA-851A732D225F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-08-24 14:51:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dV1P3EPwOfAMAogFtJAHxhuVSxg0ctb9","error":"Peer is unavailable",,"portNumber":null}'
2017-08-24 14:51:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dV1P3EPwOfAMAogFtJAHxhuVSxg0ctb9', error: 'Peer is unavailable', listeningPort: '%s''
,2017-08-24 14:51:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-08-24 14:51:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD09023D-741D-467A-939B-EE587D2D88D6 (syncValue: 77zipkreoBe4Gf49fjBdn27,eKAI93ia0)'
2017-08-24 14:51:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD09023D-741D-467A-939B-EE587,D2D88D6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:51:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:3B568BCD-8A56-4957-ABDA-851A732D225F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4D857E22-1043-4D59-866C-EE82BF5CE43B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4D857E22-1043-4D59-866C-EE82BF5CE43B", generation: 0)
2017-08-24 14:51:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4D857E22-1043-4D59-866C-EE82BF5CE43B","generation":0}'
2017-08-24 14:51:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:51:49 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:51:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C
[ThaliCore] Advertiser: session connected Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63437
2017-08-24 14:51:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"77zipkreoBe4Gf49fjBdn27eKAI93ia0",,"error":null,"portNumber":63437}'
2017-08-24 14:51:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '77zipkreoBe4Gf49fjBdn27eKAI93ia0', error: 'null', listeningPort: '63437''
,ok 210 should be equal
,2017-08-24 14:51:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3CB5059A-D11F-4536-8716-32BED6C97CD6 (syncValue: 4gxu8uJeTGdqiizOb9AZstA4MoAt6awJ)'
,2017-08-24 14:51:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:51:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C
,[ThaliCore] Session.session(_:peer:didChange:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63441
2017-08-24 14:51:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4gxu8uJeTGdqiizOb9AZstA4MoAt6awJ",,"error":null,"portNumber":63441}'
,2017-08-24 14:51:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4gxu8uJeTGdqiizOb9AZstA4MoAt6awJ', error: 'null', listeningPort: '63441''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559
[ThaliCore] Advertiser: session connected Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4D857E22-1043-4D59-866C-EE82BF5CE43B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4D857E22-1043-4D59-866C-EE82BF5CE43B", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559
,[ThaliCore] Session.session(_:peer:didChange:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 ,14:52:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-08-24 14:52:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B3AA7804-57E2-44E7-AC1A-8,164EB411284
2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
[ThaliCore] BrowserManager.disconnect peer:FD09023D-741D-467A-939B-EE587D2D88D6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63437
[ThaliCore] Sess,ion.disconnect() peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A9F29061-D330-4331-BAAD-D8815E7AF559 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:A9F29061-D330-4331-BAAD-D8815E7AF559
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:3CB5059A-D11F-4536-8716-32BED6C97CD6
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63441
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
,2017-08-24 14:52:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B054D716-015C-4B39-BA10-2E5A76273F7C state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B3AA7804-57E2-44E7-AC1A-8164EB411284", generation: 0)
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.deinit peer:A9F29061-D330-4331-BAAD-D8815E7AF559
,# setup
,2017-08-24 14:52:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4gxu8uJeTGdqiizOb9AZstA4MoAt6awJ","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 63443
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BB5CF9B6-91FF-458D-826A-E357F5135E10
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:52:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E06D21D9-48B8-45E6-BEF1-5B30C9C3EC47
[ThaliCore] Browser.startList,ening
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:52:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
2017-08-24 14:52:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD09023D-741D-467A-939B-EE587D2D88,D6","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
2017-08-24 14:52:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD09023D-741D-467A-939B-EE587D2D88D6, (syncValue: EHgtYClNQy1KCOrEhzL3jQekBMh843xG)'
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-08-24 14:52:03 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3CB5059A-D11F-4536-8716-32BED6C97CD6","generation":0}'
2017-08-24 14:52:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-,24 14:52:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
2017-08-24 14:52:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-08-24 14:52:05 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BB5CF9B6-91FF-458D-826A-E357F5135E10:0
2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already, running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-08-24 14:52:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,D09023D-741D-467A-939B-EE587D2D88D6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,D09023D-741D-467A-939B-EE587D2D88D6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276
[ThaliCore] Advertiser: session connected Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3CB5059A-D11F-4536-8716-32BED6C97CD6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3CB5059A-D11F-4536-8716-32BED6C97CD6", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,D09023D-741D-467A-939B-EE587D2D88D6", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276
,[ThaliCore] Session.session(_:peer:didChange:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD09023D-741D-467A-939B-EE587D2D88D6:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "FD09023D-741D-467A-939B-EE587D2D88D6", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:FD09023D,-741D-467A-939B-EE587D2D88D6 error: max retries exceeded
2017-08-24 14:52:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EHgtYClNQy1KCOrEhzL3jQekBMh843xG","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:52:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EHgtYClNQy1KCOrEhzL3jQekBMh843xG', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:52:14 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-08-24 14:52:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 01C1451B-604C-4664-8679-5A413158C4CD (syncValue: Pjc8LRj,Hq5O0gG44ChD04LS5Ja2Lh01I)'
2017-08-24 14:52:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:01C1451B-604C,-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-08-24 14:52:14 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t!'
,2017-08-24 14:52:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:FD09023D-741D-467A-939B-EE587D2D88D6:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:01C1451B-604C-4664-8679-5A413158C4CD:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE095084-4180-45BE-B90B-84AF67A11861
[ThaliCore] Advertiser: session connected Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AE095084-4180-45BE-B90B-84AF67A11861 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:01C1451B-604C-4664-8679-5A413158C4CD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:01C1451B-604C-4664-8679-5A413158C4CD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63462
2017-08-24 14:52:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Pjc8LRjHq5O0gG44ChD04LS5Ja2Lh01I",,"error":null,"portNumber":63462}'
2017-08-24 14:52:18 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Pjc8LRjHq5O0gG44ChD04LS5Ja2Lh01I', error: 'null', listeningPort: '63462''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-08-24 14:52:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4 (syncValue: dKGwehgIgXqzECixE0DxYiU4VIcmgOgI)'
,2017-08-24 14:52:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:52:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AE095084-4180-45BE-B90B-84AF67A11861
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE095084-4180-45BE-B90B-84AF67A11861 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63468
2017-08-24 14:52:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dKGwehgIgXqzECixE0DxYiU4VIcmgOgI","error":null,"portNumber":63468}'
,2017-08-24 14:52:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dKGwehgIgXqzECixE0DxYiU4VIcmgOgI', error: 'null', listeningPort: '63468''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:52:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BB5CF9B6-91FF-458D-826A-E357F5135E10
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:01C1451B-604C-4664-8679-5A413158C4CD
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCo,re] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63462
[ThaliCore] Session.disconnect() peer:01C1451B-604C-4664-8679-5A413158C4CD:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:05F882CE-E9AD-437A-8E93-38CBCA840276 state: connected -> notConnected
[ThaliCore] Adv,ertiser: session notConnected Peer(uuid: "BB5CF9B6-91FF-458D-826A-E357F5135E10", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.dis,connectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AE095084-4180-45BE-B90B-84AF67A11861
,[ThaliCore] Session.deinit peer:AE095084-4180-45BE-B90B-84AF67A11861
[ThaliCore] Session.deinit peer:01C1451B-604C-4664-8679-5A413158C4CD:0
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63468
,[ThaliCore] Session.disconnect() peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:52:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-08-24 14:52:22 - DEBUG thaliMobileNativeWrapper: 'listening 63472'
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
2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:52:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'listening 63473'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E9C33E9C-3171-41AD-9EF8-796E68E7D69C
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 231 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'listening 63474'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "347F4A1E-8551-48E7-B026-E63236AFBC05", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:347F4A1E-8551-48E7-B026-E63236AFBC05
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "347F4A1E-8551-48E7-B026-E63,236AFBC05", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:347F4A1E-8551-48E7-B026-E63236AFBC05
,2017-08-24 14:52:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:347F4A1E-8551-48E7-B026-E63236AFBC05
,[ThaliCore] Advertiser.stopAdvertising() peerID:347F4A1E-8551-48E7-B026-E63236AFBC05
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
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'listening 63477'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
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
,ok 239 network status should have certain non-empty properties
,# teardown
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
,# error returned with bad router
,2017-08-24 14:52:25 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'listening 63478'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EA6EFA9A-88CC-4697-A944-2EBA29214393
[ThaliCore] Browser.startListening
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D3B3371E-2CA1-44C2-AE99-390715D25B00", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D3B3371E-2CA1-44C2-AE99-390715D25B00
2017-08-24 1,4:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D3B3371E-2CA1-44C2-AE99-390715D25B00
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-08-24 14:52:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'listening 63481'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CE75EAB5-AC62-4697-857C-1707B877B801
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FF86BF9A-5E24-4A6B-A962-140F629EBCA7", genera,tion: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:FF86BF9A-5E24-4A6B-A962-140F629EBCA7
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:52:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
,# teardown
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}]'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:FF86BF9A-5E24-4A6B-A962-140F629EBCA7
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
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
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'listening 63483'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5E3785B9-407C-4038-806B-343CFB1DEBD4
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "47EB062D-D699-4CD6-AA7E-DCC3F53444AB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:47EB062D-D699-4CD6-AA7E-DCC3F53444AB
2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:47EB062D-D699-4,CD6-AA7E-DCC3F53444AB
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:52:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 247 is stopped after calling stop
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
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
,# make sure terminateConnection is properly hooked up
,2017-08-24 14:52:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,ok 253 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
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
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
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
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:30 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-08-24 14:52:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
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
,ok 259 must be stopped
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
,ok 260 must be stopped
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
,ok 261 must be stopped
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
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:32 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,ok 264 must be stopped
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
,ok 265 must be stopped
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
,ok 266 must be stopped
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
,ok 267 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'listening 63486'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:90B567DA-4B84-40F9-AB14-763270947470
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-08-24 14:52:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'listening 63487'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "18F10E0E-BAD5-4991-B814-E2914E97CC7A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:18F10E0E-BAD5-4991-B814-E2914E97CC7A
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-08-24 14:52:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
,ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:18F10E0E-BAD5-4991-B814-E2914E97CC7A
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'listening 63489'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
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
,2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'listening 63490'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6C069963-0B42-4527-91C4-1882C25F3666
[ThaliCore] Browser.st,artListening
2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:34 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E48B62AD-0B58-4F6F-A560-22AE47E2944B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E48B62AD-0B58-4F6F-A560-22AE47E2944B
,2017-08-24 14:52:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-08-24 14:52:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}]'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E48B62AD-0B58-4F6F-A560-22AE47E2944B
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'listening 63492'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D5391F65-5625-493E-986A-E0A2B4E4E9A8
,[ThaliCore] Browser.startListening
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:84CB1FE5-6959-4935-8218-C20EE2F08B52
,2017-08-24 14:52:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:52:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}]'
2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
2017-08-24 14:52:36 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4 (syncValue: Rb7QVEpOclxV9n6UfX80z9vjrKYASync)'
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-08-24 14:52:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:52:36 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
2017-08-24 14:52:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}]'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}]'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:84CB1FE5-6959-4935-8218-C20EE2F08B52:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "84CB1FE5-6959-4935-8218-C20EE2F08B52", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,A6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,A6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
2017-08-24 14:52:43 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
2017-08-24 14:52:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:52:43 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,A6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
2017-08-24 14:52:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
2017-08-24 14:52:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:52:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-24 14:52:46 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:01C1451B-604C-4664-8679-5A413158C4CD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "01C1451B-604C-4664-8679-5A413158C4CD", generation: 0)
2017-08-24 14:52:47 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}]'
2017-08-24 14:52:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","generation":0}'
,2017-08-24 14:52:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:52:47 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"01C1451B-604C-4664-8679-5A413158C4CD","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,A6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:FDA6AEB5,-34C5-4064-AB9D-571BC6BA42B4 error: max retries exceeded
2017-08-24 14:52:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Rb7QVEpOclxV9n6UfX80z9vjrKYASync","error":"Connection could not be established","portNumber":null}'
2017-0,8-24 14:52:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Rb7QVEpOclxV9n6UfX80z9vjrKYASync', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:52:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-24 14:52:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A21C39C3-4A3F-46BA-B16E-602CFA61B286 (syncValue: Oo0toKA6P0h7jGEkMAAhy4OcPiJkuBmr)'
,2017-08-24 14:52:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63504
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Oo0toKA6P0h7jGEkMAAhy4OcPiJkuBmr","error":null,"portNumber":63504}'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Oo0toKA6P0h7jGEkMAAhy4OcPiJkuBmr', error: 'null', listeningPort: '63504''
,2017-08-24 14:52:52 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [3, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-24 14:52:52 - DEBUG testUtils: 'Got response data'
,2017-08-24 14:52:52 - DEBUG testUtils: 'Got end'
,ok 279 response body should match testData
,ok 280 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:84CB1FE5-6959-4935-8218-C20EE2F08B52
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:52:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:52:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] BrowserManager.disconnect peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286
[ThaliCore] VirtualSocket.deinit vsID:17 [3]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error,:nil
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63504
[ThaliCore] BrowserRelay.d,idSocketDisconnectHandler
[ThaliCore] Session.disconnect() peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:52:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:52:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'listening 63506'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7C3D990B-F082-4B44-B65E-12601E6492A8
[ThaliCore] Browser.st,artListening
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:52:53 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:,283DB3E7-9F5D-4C43-8B90-8282EA781BA5
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:52:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-08-24 14:52:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
2017-08-24 14:52:53 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}]'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A21C39C3-4A3F-46BA-,B16E-602CFA61B286","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","peerAvailable":true,"generation":0,"portNumber":nu,l[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
l}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A21C39C3-4A3F-46BA-B16E-602CFA61B286 (syncValue: 32BAy1uQcvpeO69bvqdrKUCqShmL8HmI)'
2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A2,1C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB,9D-571BC6BA42B4", generation: 0)
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}]'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}]'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:283DB3E7-9F5D-4C43-8B90-8282EA781BA5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
2017-08-24 14:52:54 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation":0}]'
2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserMana,ger.foundPeerHandler peer:Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","peerAvai,l,able":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-24 14:52:54 - ,DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}]'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:52:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:52:54 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,1C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3304B754-50D5-4361-A23C-5327C08FA6E5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3304B754-50D5-4361-A23C-5327C08FA6E5", generation: 0)
2017-08-24 14:52:57 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}]'
2017-08-24 14:52:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","generation":0}'
,2017-08-24 14:52:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:52:57 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"3304B754-50D5-4361-A23C-5327C08FA6E5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4", generation: 0)
2017-08-24 14:53:02 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}]'
2017-08-24 14:53:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","generation":0}'
,2017-08-24 14:53:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:53:02 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"FDA6AEB5-34C5-4064-AB9D-571BC6BA42B4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,1C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:A21C39C3,-4A3F-46BA-B16E-602CFA61B286 error: max retries exceeded
,2017-08-24 14:53:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"32BAy1uQcvpeO69bvqdrKUCqShmL8HmI","error":"Connection could not be established","portNumber":null}'
,2017-08-24 14:53:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '32BAy1uQcvpeO69bvqdrKUCqShmL8HmI', error: 'Connection could not be established', listeningPort: '%s''
,2017-08-24 14:53:04 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-24 14:53:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF (syncValue: uOxihKZ2mAL5EWbpCgoLFrDC29qVvEBw)'
,2017-08-24 14:53:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:62CD5FD8-A21F-4579-A1FA-50B2290E7C06
[ThaliCore] Advertiser: session connected Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:62CD5FD8-A21F-4579-A1FA-50B2290E7C06 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:1E633700-B9A3-46C4-936E-30495EC01CE7
[ThaliCore] Advertiser: session connected Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[T,haliCore] Session.session(_:peer:didChange:) peer:1E633700-B9A3-46C4-936E-30495EC01CE7 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A21C39C3-4A3F-46BA-B16E-602CFA61B286:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A21C39C3-4A3F-46BA-B16E-602CFA61B286", generation: 0)
,2017-08-24 14:53:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}]'
,2017-08-24 14:53:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","generation":0}'
,2017-08-24 14:53:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-08-24 14:53:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A21C39C3-4A3F-46BA-B16E-602CFA61B286","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1E633700-B9A3-46C4-936E-30495EC01CE7
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E633700-B9A3-46C4-936E-30495EC01CE7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:62CD5FD8-A21F-4579-A1FA-50B2290E7C06
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:1E633700-B9A3-46C4-936E-30495EC01CE7
[ThaliCore] Session.startOutputStream(with:) peer:1E633700-B9A3-46C4-936E-30495EC01CE7
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [3, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:62CD5FD8-A21F-4579-A1FA-50B2290E7C06 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:62CD5FD8-A21F-4579-A1FA-50B2290E7C06
[ThaliCore] Session.startOutputStream(with:) peer:62CD5FD8-A21F-4579-A1FA-50B2290E7C06
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [3, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63522
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uOxihKZ2mAL5EWbpCgoLFrDC29qVvEBw","error":null,"portNumber":63522}'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uOxihKZ2mAL5EWbpCgoLFrDC29qVvEBw', error: 'null', listeningPort: '63522''
,2017-08-24 14:53:08 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [3, 18, 19, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-24 14:53:08 - DEBUG testUtils: 'Got response data'
,2017-08-24 14:53:08 - DEBUG testUtils: 'Got end'
,ok 282 response body should match testData
,ok 283 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:283DB3E7-9F5D-4C43-8B90-8282EA781BA5
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1E633700-B9A3-46C4-936E-30495EC01CE7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket, error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disc,onnecting:true
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLoc,alizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:18 [3, 19, 20]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] Session.disconnect() peer:1E633700-B9A3-46C4-936E-30495EC01CE7
[ThaliCore] VirtualSocket.closeStreams,() vsID:19
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [3, 20]
,[ThaliCore] BrowserManager.disconnect peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63522
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:20 [3]
,[ThaliCore] Session.disconnect() peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
,[ThaliCore] Session.deinit peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
,[ThaliCore] BrowserRelay.deinit
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:62CD5FD8-A21F-4579-A1FA-50B2290E7C06 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "283DB3E7-9F5D-4C43-8B90-8282EA781BA5", generation: 0)
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-08-24 14:53:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,[ThaliCore] Session.deinit peer:1E633700-B9A3-46C4-936E-30495EC01CE7
,# teardown
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:09 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:53:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-08-24 14:53:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 286 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:10 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:53:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'listening 63524'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:05585B5F-4A70-4E7A-B6B5-2FAF229801C2
[ThaliCore] Browser.startListening
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-08-24 14:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-08-24 14:53:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:089F34F7-2665-42AE-B516-FAD462A067E4
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-08-24 14:53:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-08-24 14:53:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF (syncValue: 57EzmFVbAgqmOSSCb9mBBHuKff6KAxb2)'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}]'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:11 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","generation":0}]'
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","generation":0}'
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:53:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:089F34F7-2665-42AE-B516-FAD462A067E4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9F56726-E546-46CD-B1A6-ABCA2203A872:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9F56726-E546-46CD-B1A6-ABCA2203A872", generation: 0)
2017-08-24 14:53:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","generation":0}]'
2017-08-24 14:53:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","generation":0}'
,2017-08-24 14:53:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:53:13 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-24 14:53:13 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","peerAvailable":true,"generation":0,"portNumber":null}'
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
[ThaliCore] Session.disconnect() peer:95,B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,5B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:93922256-C7C8-4DB9-B61E-DC3CCB8151D5:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "93922256-C7C8-4DB9-B61E-DC3CCB8151D5", generation: 0)
2017-08-24 14:53:18 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}]'
2017-08-24 14:53:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","generation":0}'
,2017-08-24 14:53:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:53:18 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"93922256-C7C8-4DB9-B61E-DC3CCB8151D5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76
[ThaliCore] Advertiser: session connected Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76 state: notConnected -> connecting
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
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
2017-08-24 14:53:21 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation":0}]'
2017-08-24 14:53:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","generation":0}'
,2017-08-24 14:53:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","peerAvailable":false,"generation":null,"portNumber":null}'
2017-08-24 14:53:21 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76
[ThaliCore] Session.startOutputStream(with:) peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [3, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF error: ma,x retries exceeded
,2017-08-24 14:53:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"57EzmFVbAgqmOSSCb9mBBHuKff6KAxb2","error":"Connection could not be established","portNumber":null}'
2017-08-24 14:53:22 - DEBUG thaliMobileNativeTestUtils: 'Got mul,tiConnectResolved -syncValue: '57EzmFVbAgqmOSSCb9mBBHuKff6KAxb2', error: 'Connection could not be established', listeningPort: '%s''
2017-08-24 14:53:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-08-24 14:53:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 78AAC586-1402-4A0D-8C29-BFD492D2F632 (syncValue: XPsiMt6JYQeTkCBuTrF4eBYigkAos0Bq)'
,2017-08-24 14:53:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:95B1BAF0-32BB-4CB0-ACFC-A6F2EAD6A7AF:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63538
,2017-08-24 14:53:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XPsiMt6JYQeTkCBuTrF4eBYigkAos0Bq","error":null,"portNumber":63538}'
,2017-08-24 14:53:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XPsiMt6JYQeTkCBuTrF4eBYigkAos0Bq', error: 'null', listeningPort: '63538''
,2017-08-24 14:53:25 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [3, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-08-24 14:53:25 - DEBUG testUtils: 'Got response data'
,2017-08-24 14:53:25 - DEBUG testUtils: 'Got end'
,ok 287 response body should match testData
,ok 288 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:089F34F7-2665-42AE-B516-FAD462A067E4
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] VirtualSocket.deinit vsID:22 [3, 21]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-08-24 14:53:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] Virt,ualSocket.closeStreams() vsID:21
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [3]
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:78AAC586-1402-4A0D-8C29-BFD492D2F632
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63538
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "089F34F7-2665-42AE-B516-FAD462A067E4", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-08-24 14:53:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-08-24 14:53:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XPsiMt6JYQeTkCBuTrF4eBYigkAos0Bq","error":"Session disconnected","portNumber":null}'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.deinit peer:F4FEB4B5-21D2-498B-8BDB-82FEC485EE76
,# will fail bad PSK connection between peers
,ok 290 FIX ME, PLEASE!!!
,# teardown
,ok 291 must be stopped
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
,ok 292 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:27 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-08-24 14:53:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-08-24 14:53:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,2017-08-24 14:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-08-24, 14:53:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 63540'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 303 error should be null
ok 304 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 305 error should be null
,ok 306 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 307 error should be null
,ok 308 error should be null
,# setup
,ok 309 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'listening 63541'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D3CDAA72-BAEA-48B7-AD55-7C662BCBF3D3
[ThaliCore] Browser.st,artListening
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 310 error should be null
ok 311 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 312 error should be null
ok 313 error should be null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:78AAC586-1402-4A0D-8C29-BFD492D2F632:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "78AAC586-1402-4A0D-8C29-BFD492D2F632", generation: 0)
2017-08-24 14:53:29 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","generation":0}]'
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9F56726-E546-46CD-B1A6-ABCA2203A872:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9F56726-E546-46CD-B1A6-ABCA2203A872", generation: 0)
2017-08-24 14:53:29 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","peerAvailable":true,"generation":0,"portNumber":null}'
2017-08-24 14:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged ,from handlePeer {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event fro,m native layer [{"peerAvailable":true,"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","generation":0}]'
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","generation":0}'
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-08-24 14:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-08-24 14:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"78AAC586-1402-4A0D-8C29-BFD492D2F632","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-08-24 14:53:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"D9F56726-E546-46CD-B1A6-ABCA2203A872","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-08-24 14:53:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-08-24 14:53:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-08-24 14:53:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 314 error should be null
,ok 315 error should be null
,# setup
,ok 316 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'listening 63542'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA6F85E1-80BA-4BEF-8173-4527962B5C83", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EA6F85E1-80BA-4BEF-8173-4527962B5C83
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 317 error should be null
ok 318 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA6F85E1-80BA-4BEF-8173-4527962B5C83", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:EA6F85E1-80BA-4BEF-8173-4527962B5C83
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 319 error should be null
,ok 320 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:EA6F85E1-80BA-4BEF-8173-4527962B5C83
[ThaliCore] Advertiser.stopAdvertising() peerID:EA6F85E1-80BA-4BEF-8173-4527962B5C83
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 321 error should be null
,ok 322 error should be null
,# setup
,ok 323 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'listening 63545'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
ok 324 error should be null
ok 325 error should be null
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 326 error should be null
,ok 327 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-08-24 14:53:31 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-08-24 14:53:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-08-24 14:53:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 328 error should be null
ok 329 error should be null
,# setup
,ok 330 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-08-24 14:53:31 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 331 This should not cause wifi to fail
,ok 332 native router should be bad
,# teardown
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'listening 63546'
,ok 336 first call should succeed
,ok 337 first call should succeed
,ok 338 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-08-24 14:53:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-08-24 14:53:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-08-24 14:53:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 339 error should be null
,ok 340 error should be null
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
,2017-08-24 14:53:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"98031a92-b33c-4792-99d0-07dc848cde01","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 348 should be called once
ok 349 should not have been called more than once
,# teardown
,2017-08-24 14:53:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"98031a92-b33c-4792-99d0-07dc848cde01","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-08-24 14:53:33 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-08-24 14:53:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:53:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:53:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:53:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:53:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:54:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:54:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:55:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:55:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:56:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:56:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:57:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:57:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-08-24 14:58:33 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,nts plugin delay interval'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-08-24 14:58:33 - INFO Coordi,natedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueu,e and run in order'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-08-24 14,:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-08-24 14:58:33 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-08-24 14:58:33 - IN,FO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
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
    at SubError@/private/var/containers/Bundle/Application/E0,7BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_m,odules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-08-24 14:58:33 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-08-24 14:58:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:58:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:58:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 14:59:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 14:59:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:00:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:00:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:01:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:01:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:02:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:02:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:03:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:03:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:04:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:04:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:05:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:05:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:06:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:06:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:07:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:07:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4,497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:08:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:08:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-08-24 15:08:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-449,7-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-08-24 15:08:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E07BBE2E-3C26-4497-BEEA-AFC2D07B5FA6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
