#### Test 145917619d0aee2c_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/145917619d0aee2c/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,(lldb) command source -s 0 '/tmp/7E38BD8F-22BE-4DB9-B364-4D2B056E579D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/7E38BD8F-22BE-4DB9-B364-4D2B056E579D/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/145917619d0aee2c/build_ios/ThaliTest.app"
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,Current executable set to '/Users/thali/Github/CI/builder/builds/145917619d0aee2c/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50587"
,(lldb)     command script import "/tmp/7E38BD8F-22BE-4DB9-B364-4D2B056E579D/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
,JXcore Cordova bridge is ready
JXcore engine is started
,2017-10-11 11:46:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:46:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:46:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:46:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:46:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:46:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:46:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D7E2F698-0B1C-4667-B1D7-CC4F65FD6C31", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D7E2F698-0B1C-4667-B1D7-CC4F65FD6C31
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5D91E325-2A85-4B2D-B9B4-,8D17EA1F391B
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:167F4753-B3FF-476A-8EAB-636FC8F06F88
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F746B10C-EC6F-4926-804A-3A71B1E26144", generation: 0)
[Tha,liCore] Advertiser.startAdvertising with peerID:F746B10C-EC6F-4926-804A-3A71B1E26144
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F746B10C-EC6F-4926-804A-3A71B1E26144:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F746B10C-EC6F-4926-804A-3A71B1E26144", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-10-11 11:46:50 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  1.735581994056702
,2017-10-11 11:46:50 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-10-11 11:46:50 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F746B10C-EC6F-4926-804A-3A71B1E26144:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F746B10C-EC6F-4926-804A-3A71B1E26144", generation: 0)
,2017-10-11 11:46:54 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-10-11 11:46:54 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-10-11 11:46:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-10-11 11:46:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-10-11 11:46:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-10-11 11:46:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-10-11 11:46:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-10-11 11:46:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-10-11 11:46:58 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-10-11 11:46:58 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-10-11 11:46:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:47:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:47:51 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-10-11 11:47:51 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-10-11 11:47:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-10-11 11:48:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
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
,ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-10-11 11:48:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:48:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:48:42 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FCCC9CB0-82ED-4195-BA3D-6E86DD4AF1F1
[ThaliCore] Browser.startListening
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-10-11 11:48:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:48:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-10-11 11:48:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:141285A4-1111-475D-88C9-5877509A568D
[ThaliCore] Browser.startListening
2017-10-11 11:48:43 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-11 11:48:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:48:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-10-11 11:48:43 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-10-11 11:48:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with tar,get ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stop,ped state).'
ok 65 Can call startListeningForAdvertisements twice without error
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
,2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-10-11 11:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-10-11 11:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2FA85A3A-61A5-493F-A0AA-83085182B86B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2FA85A3A-61A5-493F-A0AA-83085182B86B
2017-10-11 1,1:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:48:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2FA85A3A-61A5-493F-A0AA-83085182B86B
2017-10-11 11:48:49 - DEBUG tha,l,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-10-11 11:48:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:49 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3541AE70-114C-499A-AB9E-07E3821C5EA4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:3541AE70-114C-499A-AB9E-07E3821C5EA4
2017-10-11 1,1:48:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:48:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3541AE70-114C-499A-AB9E-07E3821C5EA4", generation: 1)
[ThaliCore] ,A,dvertiser.startAdvertising with peerID:3541AE70-114C-499A-AB9E-07E3821C5EA4
2017-10-11 11:48:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-11 11:48:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-11 11:48:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:48:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3541AE70-114C-499A-AB9E-07E3821C5EA4
[ThaliCore] Advertiser.stopAdvertising() peerID:3541AE70-114C-499A-AB9E-07E3821C5EA4,
2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e).'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:48:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:48:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "939B08FA-41FE-498B-B51E-E9333112CF98", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:939B08FA-41FE-498B-B51E-E9333112CF98
2017-10-11 11:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:06, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-10-11 11:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thali,Core] Browser.init(serviceType:foundPeer:lostPeer:) peer:751953E7-1ABB-49BA-AA91-10F2660D56BD
[ThaliCore] Browser.startListening
2017-10-11 11:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,t,isingActive":true}'
2017-10-11 11:49:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"route,r":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75F23093-476E-4543-93E5-6091E21DEA89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75F23093-476E-4543-93E5-6091E21DEA89", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DA861A75-8005-4738-B121-D6D2FA3CB68E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DA861A75-8005-4738-B121-D6D2FA3CB68E", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-10-11 11:49:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-10-11 11:49:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-10-11 11:49:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:939B08FA-41FE-498B-B51E-E9333112CF98
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:49:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B12CCD5C-504E-4635-8DB3-BE9514508331
,2017-10-11 11:49:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8D36BD79-DEDD-4C38-9337-2381DA31,C6BE
[ThaliCore] Browser.startListening
2017-10-11 11:49:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-10-11 11:49:30 - INFO thaliMobile: 'Received state ({"discovery,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:49:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B684C49D-590F-4A16-9CBA-CC5ED8CDA416","generation":0}'
,2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B684C49D-590F-4A16-9CBA-CC5ED8CDA416 (syncValue: 93TTBeytT6rmdFg5WvagHSENz1p2FScg)'
,2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8","generation":0}'
2017-10-11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-,11 11:49:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B12CCD5C-504E-4635-8DB3-BE9514508331:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B12CCD5C-504E-4635-8DB3-BE9514508331", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56265
2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"93TTBeytT6rmdFg5WvagHSENz1p2FScg","error":null,"portN,umber":56265}'
2017-10-11 11:49:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '93TTBeytT6rmdFg5WvagHSENz1p2FScg', error: 'null', listeningPort: '56265''
,2017-10-11 11:49:35 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-10-11 11:49:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 ,11:49:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-11 11:49:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B12CCD5C-504E-4635-8DB3-B,E9514508331
2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56265
[ThaliCore] Session.disconnect() peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
,[ThaliCore] BrowserRelay.deinit
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:49:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641
2017-10-11 1,1:49:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:49:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:49:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:40D38DB4-6925-4DA1-9246-840925B80A75
[Thal,i,Core] Browser.startListening
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-11 11:49:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
2017-10-11 11:49:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[,ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
ok 87 Can call startListeningForAdvertisements without error
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B684C49D,-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8","generation":0}'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8 (syncValue: fLh3R1iJI2kWqgF0strpa1hYb6xlIGA1)'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B684C49D-590F-4A16-9CBA-CC5ED8CDA416","generation":0}'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
2017-10-11 11:49:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9F70A025-7FB6-44F8-842A-A7168F9BD13B","generation":0}'
2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:49:42 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
,2017-10-11 11:49:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"693ACD69-7D6C-45C9-A0EE-2855E12F155B","generation":0}'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:49:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF4CF963-A10F-4CDD-9A86-7AE2A53CC641:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF4CF963-A10F-4CDD-9A86-7AE2A53CC641", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
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
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C1,FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-11 11:49:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fLh3R1iJI2kWqgF0strpa1hYb6xlIGA1","error":"Peer is unavailable",,"portNumber":null}'
2017-10-11 11:49:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fLh3R1iJI2kWqgF0strpa1hYb6xlIGA1', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-11 11:49:50 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-11 11:49:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B684C49D-590F-4A16-9CBA-CC5ED8CDA416 (syncValue: eVYnfycuLxLJs1Q846WgLed,G7VvP7Dem)'
2017-10-11 11:49:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B684C49D-590F-4A16-9CBA-CC5ED,8CDA416:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-11 11:49:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:49:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C1FE7B04-FEF8-45A3-BC71-B2E4C17DCED8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B6,84C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B6,84C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B684C49D-590F-4A16-9CBA-CC5ED8CDA416", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-10-11 11:49:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eVYnfycuLxLJs1Q846WgLedG7VvP7Dem","error":"Peer is unavailable",,"portNumber":null}'
2017-10-11 11:49:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eVYnfycuLxLJs1Q846WgLedG7VvP7Dem', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-11 11:49:55 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-11 11:49:55 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9F70A025-7FB6-44F8-842A-A7168F9BD13B (syncValue: GYl4Szl9QQ3FjuYwbEleiHZ,WYYBjeXe7)'
2017-10-11 11:49:55 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F70A025-7FB6-44F8-842A-A7168,F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-10-11 11:49:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B684C49D-590F-4A16-9CBA-CC5ED8CDA416:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56273
2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GYl4Szl9QQ3FjuYwbEleiHZWYYBjeXe7",,"error":null,"portNumber":56273}'
2017-10-11 11:49:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GYl4Szl9QQ3FjuYwbEleiHZWYYBjeXe7', error: 'null', listeningPort: '56273''
,Connecting to the localhost:56273
Connected to the localhost:56273
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
[ThaliCore] Session.startOutputStream(with:) peer:9F70A025-7FB6-,44F8-842A-A7168F9BD13B:0
2017-10-11 11:49:59 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:1
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
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,2017-10-11 11:49:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 ,11:49:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-11 11:49:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BF4CF963-A10F-4CDD-9A86-7,AE2A53CC641
2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:49:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56273
[ThaliCore] Session.disconnect() p,eer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-10-11 11:49:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-10-11 11:49:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:CF3EAD01-0759-464B-B522-6E5D1376B433
,2017-10-11 11:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 11:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-10-11 11:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D9BAB450-56B2-4619-8D12-1D81A214243C
[ThaliCore] Browser.startListening
,2017-10-11 11:50:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-10-11 11:50:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-10-11 11:50:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
2017-10-11 11:50:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9F70A025-7FB6-44F8-842A-A7168F9BD13B","generation":0}'
2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9F70A025-7FB6-44F8-842A-A7168F9BD13B, (syncValue: fyEAydFPUDkrCWHXPoD4p8TTY3Ty4XS3)'
,2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F,70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9F70A025-7FB6-44F8,-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "693ACD69-7D6C-45C9-A0,EE-2855E12F155B", generation: 0)
2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"693ACD69-7D6C-45C9-A0EE-2855E12F155B","generation":0}'
2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils:, 'Already running test!'
2017-10-11 11:50:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA","generation":0}'
2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF3EAD01-0759-464B-B522-6E5D1376B433:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B8643CF2-FE60-44D6-A9DE-05A1F25612CE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B8643CF2-FE60-44D6-A9DE-05A1F25612CE", generation: 0)
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B8643CF2-FE60-44D6-A9DE-05A1F25612CE","generation":0}'
2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-10-11 11:50:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
[ThaliCore] Advertiser: session connected Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9F,70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:9F70A025,-7FB6-44F8-842A-A7168F9BD13B error: max retries exceeded
2017-10-11 11:50:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fyEAydFPUDkrCWHXPoD4p8TTY3Ty4XS3","error":"Connection could not be established","portNumber":null}'
2017-1,0-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fyEAydFPUDkrCWHXPoD4p8TTY3Ty4XS3', error: 'Connection could not be established', listeningPort: '%s''
,2017-10-11 11:50:11 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 693ACD69-7D6C-45C9-A0EE-2855E12F155B (syncValue: hwzkEaO,uTLiAeFZF9EacpMtOOY04m1TO)'
,2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-10-11 11:50:11 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
[ThaliCore] Session.startOutputStream(with:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9F70A025-7FB6-44F8-842A-A7168F9BD13B:0
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9F70A025-7FB6-44F8-842A-A7168F9BD13B", generation: 0),
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
[ThaliCore] Session.startOutputStream(with:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
[ThaliCore] Session.startOutputStream(with:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4, [2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
,[ThaliCore] Session.session(_:peer:didChange:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:69,3ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,93ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "693ACD69-7D6C-45C9-A0EE-2855E12F155B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:2
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:3
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received (12288 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:3
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received all data: 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,[ThaliCore] Session.deinit peer:693ACD69-7D6C-45C9-A0EE-2855E12F155B:0
[ThaliCore] BrowserRelay.deinit
,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'
2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:2
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:2
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:2
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:2
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:2 [3, 4]
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:3
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:4
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received (8192 bytes):'
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received (8192 bytes):'
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:,3
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:3
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:3
2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server data flushed'
[ThaliCore], VirtualSocket.readDataFromInputStream() read: 0 vsID:3
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4]
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:,4
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:4
[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:4
2017-10-11 11:50:14 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 0 vsID:4
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
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
,[ThaliCore] BrowserRelay.deinit
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
2017-10-11 11:50:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hwzkEaOuTLiAeFZF9EacpMtOOY04m1TO","error":"Peer is unavailable",,"portNumber":null}'
2017-10-11 11:50:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hwzkEaOuTLiAeFZF9EacpMtOOY04m1TO', error: 'Peer is unavailable', listeningPort: '%s''
,2017-10-11 11:50:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-10-11 11:50:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA (syncValue: wKlV9D0vO5LGJWI5EYJOPFk,KuNRkpTvA)'
2017-10-11 11:50:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D,4AC92FA:0
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
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56298
2017-10-11 11:50:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wKlV9D0vO5LGJWI5EYJOPFkKuNRkpTvA",,"error":null,"portNumber":56298}'
2017-10-11 11:50:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wKlV9D0vO5LGJWI5EYJOPFkKuNRkpTvA', error: 'null', listeningPort: '56298''
,Connecting to the localhost:56298
,Connecting to the localhost:56298
Connecting to the localhost:56298
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] Session.startOutputStream(with:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
,Connected to the localhost:56298
,Connected to the localhost:56298
,[ThaliCore] Session.startOutputStream(with:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
Connected to the localhost:56298
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [5, 6]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [5, 6, 7]
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:5
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:5
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1379 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:5
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 284 vsID:5
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2149 vsID:5
,ok 92 correct string length
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:6
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:6
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 4096 vsID:6
,ok 93 correct string length
,2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] VirtualSocket.writeDataToOutputStream len:16384 count:1 vsID:7
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] VirtualSocket.writePendingData() to write:16384 written:16384 count:0 vsID:7
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-10-11 11:50:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnOutputStream hasSpaceAvailable vsID:7
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
ok 95 got the same data b,ack
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [5, 7]
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2190 vsID:7
[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 3285 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 1095 vsID:7
,[ThaliCore] VirtualSocket.readDataFromInputStream() read: 2149 vsID:7
,ok 96 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [5]
,# teardown
,2017-10-11 11:51:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-10-11 ,11:51:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-10-11 11:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CF3EAD01-0759-464B-B522-6,E5D1376B433
2017-10-11 11:51:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-10-11 11:51:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56298
[ThaliCore] Session.disconnect() p,eer:CA4F3AF0-C6E6-4A7D-ABF3-25A3D4AC92FA:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "CF3EAD01-0759-464B-B522-6E5D1376B433", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:AD3E6ED2-0B78-4737-B11D-2B6AC00B67F1
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-10-11 11:52:18 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-10,-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGG,ER result: passed - enqueue and run in order'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en,queueAtTop'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously',
2017-10-11 11:52:18 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
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
    at SubError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest,.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
,    at timeoutTimeout@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-10-11 11:52:18 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-10-11 11:52:48 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-10-11 11:52:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:52:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:52:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:52:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:53:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:53:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:54:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:54:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4,BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:55:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:55:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:56:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:56:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:57:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:57:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:58:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:58:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 11:59:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 11:59:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:00:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:00:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:01:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:01:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:02:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:02:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:03:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4,BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:03:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:03:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:03:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:03:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:03:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:04:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:04:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:05:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:05:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4,BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:06:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:06:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-10-11 12:07:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF,9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-10-11 12:07:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0BAE7834-5236-4BF9-BB72-5DDAFCBBE62A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
