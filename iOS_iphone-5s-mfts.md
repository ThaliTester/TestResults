#### Test 132007755285fc7e_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/132007755285fc7e/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10).
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/F4BED067-2816-4F48-9F71-890C3D14B271/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/F4BED067-2816-4F48-9F71-890C3D14B271/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/132007755285fc7e/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/132007755285fc7e/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:55599"
,(lldb)     command script import "/tmp/F4BED067-2816-4F48-9F71-890C3D14B271/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
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
,2017-07-24 12:11:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:11:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:11:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:11:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:11:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:11:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:11:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "570816EA-4AF2-466D-9901-0AF1DA804FF5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:570816EA-4AF2-466D-9901-0AF1DA804FF5
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DEF7BAB3-58E7-4B6E-839B-6F8FFFA301F1
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F29F4C1C-,170B-4C89-8A1B-722A2933D7D7
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4FB4ADEB-636C-4B3D-876D-1A20C451E03C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4FB4ADEB-636C-4B3D-876D-1A20C451E03C
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4FB4ADEB-636C-4B3D-876D-1A20C451E03C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4FB4ADEB-636C-4B3D-876D-1A20C451E03C", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-24 12:11:57 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
,Number of failed tests:  0
,Number of ignored tests:  0
,Total duration:  1.685488939285278
,2017-07-24 12:11:57 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
2017-07-24 12:11:57 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4FB4ADEB-636C-4B3D-876D-1A20C451E03C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4FB4ADEB-636C-4B3D-876D-1A20C451E03C", generation: 0)
,2017-07-24 12:12:01 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-24 12:12:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-24 12:12:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-24 12:12:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-24 12:12:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-24 12:12:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-24 12:12:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-24 12:12:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-24 12:12:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-24 12:12:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-24 12:12:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-24 12:12:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-24 12:12:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-24 12:12:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-24 12:12:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-24 12:12:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-24 12:12:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-24 12:12:05 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-24 12:12:05 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-24 12:12:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:12:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:12:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:12:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:12:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:12:20 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-24 12:12:20 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-24 12:12:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
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
,2017-07-24 12:12:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-24 12:12:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7C0D08CF-7560-4F95-8180-0D759F9311CE
,[ThaliCore] Browser.startListening
,2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
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
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9AB421F2-5B52-4FFE-8EA9-BB4B5E0F02F4
[ThaliCore] Browser.startListening
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:12:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 12:12:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-2,4 12:12:53 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:12:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
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
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "45CCBA51-C43F-4614-A4D8-FDA1865D95FF", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:45CCBA51-C43F-4614-A4D8-FDA1865D95FF
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:54, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 12:12:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising() peerID:45CCBA51-C43F-4614-A4D8-FDA1865D95FF
2017-07-24 12:12:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:54 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F3322D80-257F-4B27-A8D9-69FE81F8F3A9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F3322D80-257F-4B27-A8D9-69FE81F8F3A9
2017-07-24 1,2:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F3322D80-257F-4B27-A8D9-69FE81F8F3A9", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:F3322D80-257F-4B27-A8D9-69FE81F8F3A9
,2017-07-24 12:12:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:12:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F3322D80-257F-4B27-A8D9-69FE81F8F3A9
,[ThaliCore] Advertiser.stopAdvertising() peerID:F3322D80-257F-4B27-A8D9-69FE81F8F3A9
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:12:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:12:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9AC440CA-971E-4F78-BB2F-BC94E406C8C1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9AC440CA-971E-4F78-BB2F-BC94E406C8C1
2017-07-24 12:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:12:58, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:12:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 74 Can call startUpdateAdvertisingAndListeningwithout error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D0AE9208-6161-4AFC-8D1B-5AD0ABB226AC
[ThaliCore] Browser.startListening
2017-07-24 12:12:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:12:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:12:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AC440CA-971E-4F78-BB2F-BC94E406C8C1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AC440CA-971E-4F78-BB2F-BC94E406C8C1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E4B9B596-003C-4812-A751-BA727FF36A55:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E4B9B596-003C-4812-A751-BA727FF36A55", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:00 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9AC440CA-971E-4F78-BB2F-BC94E406C8C1
2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:13:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:13:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:13:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:75DD76C5-36DA-429E-9B49-8B4F23A6900D
2017-07-24 1,2:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F874D147-C68A-491B-866D-E7AF25C37560
[ThaliCore] Browser.startListe,ning
2017-07-24 12:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:13:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tru,e}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
2017-07-24 12:13:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7CD4A326-EA8C-4C7A-9109-4C3844A1A542","generation":0}'
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7CD4A326-EA8C-4C7A-9109-4C3844A1A542 (syncValue: L15Jv4LrWiJL1b1exdkoRfxByk9q6Uie)'
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6E6B3997-56C8-4EBD-8540-DB22D429A7D1","generation":0}'
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:75DD76C5-36DA-429E-9B49-8B4F23A6900D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "75DD76C5-36DA-429E-9B49-8B4F23A6900D", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61766
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"L15Jv4LrWiJL1b1exdkoRfxByk9q6Uie","error":null,"portNumber":61766}'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'L15Jv4LrWiJL1b1exdkoRfxByk9q6Uie', error: 'null', listeningPort: '61766''
,2017-07-24 12:13:08 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-24 12:13:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:13:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:13:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:75DD76C5-36DA-429E-9B49-8B4F23A6900D
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:13:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61766
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "7CD4A326-EA8C-4C7A-9109-4C3844A1A542", generation: 0)
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:13:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 12:13:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"L15Jv4LrWiJL1b1exdkoRfxByk9q6Uie","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:7CD4A326-EA8C-4C7A-9109-4C3844A1A542:0
,[ThaliCore] BrowserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:870B7B74-771B-4859-AAB3-509F704123AD
2017-07-24 1,2:13:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:559AC4E1-7532-4912-A9EF-91218AB9ACC4
[ThaliCore] Browser.startListening
2017-07-24 12:13:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-24 12:13:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
2017-07-24 12:13:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6E6B3997-56C8-4EBD-8540-DB22D429A7D1","generation":0}'
2017-07-24 12:13:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6E6B3997-56C8-4EBD-8540-DB22D429A7D1, (syncValue: ydtBTSyJ39qN2fuLy7fBc02WaVtj0miZ)'
2017-07-24 12:13:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D42,9A7D1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
2017-07-24 12:13:10 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0","generation":0}'
2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:10 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
,2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"21ED5147-420B-4877-B71D-3C4D9F498B8D","generation":0}'
,2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:870B7B74-771B-4859-AAB3-509F704123AD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:991B4017-09A7-43E7-8D5A-F7E501EA632D
[ThaliCore] Advertiser: session connected Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:991B4017-09A7-43E7-8D5A-F7E501EA632D state: notConnected -> connecting
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
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:991B4017-09A7-43E7-8D5A-F7E501EA632D
,[ThaliCore] Session.session(_:peer:didChange:) peer:991B4017-09A7-43E7-8D5A-F7E501EA632D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:991B4017-09A7-43E7-8D5A-F7E501EA632D
[ThaliCore] Session.startOutputStream(with:) peer:991B4017-09A7-43E7-8D5A-F7E501EA632D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1, [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:13:15 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 12:13:15 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-24 12:13:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-24 12:13:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
,[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6E,6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "6E6B3997-56C8-4EBD-8540-DB22D429A7D1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:6E6B3997,-56C8-4EBD-8540-DB22D429A7D1 error: max retries exceeded
2017-07-24 12:13:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ydtBTSyJ39qN2fuLy7fBc02WaVtj0miZ","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ydtBTSyJ39qN2fuLy7fBc02WaVtj0miZ', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:13:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0 (syncValue: XEP6H4D,FFWIfScB5SurRm9u2917b8jNA)'
2017-07-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C59D3ABD-41F1,-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6E6B3997-56C8-4EBD-8540-DB22D429A7D1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61773
2017-07-24 12:13:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XEP6H4DFFWIfScB5SurRm9u2917b8jNA",,"error":null,"portNumber":61773}'
2017-07-24 12:13:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XEP6H4DFFWIfScB5SurRm9u2917b8jNA', error: 'null', listeningPort: '61773''
Connecting to the localhost:61773
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
Connected to the localhost:61773
,2017-07-24 12:13:23 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 12:13:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [1, 2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 88 got the same data back
,# teardown
,2017-07-24 12:13:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 [2]
,2017-07-24 12:13:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:870B7B74-771B-4859-AAB3-509F704123AD
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61773
[ThaliCore] Session.disconnect() p,eer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:991B4017-09A7-43E7-8D5A-F7E501EA632D state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "870B7B74-771B-4859-AAB3-509F704123AD", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:991B4017-09A7-43E7-8D5A-F7E501EA632,D
,[ThaliCore] Session.deinit peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-24 12:13:25 - DEBUG thaliMobileNa,tiveWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] AdvertiserRelay.deinit
# setup
,[ThaliCore] Session.deinit peer:991B4017-09A7-43E7-8D5A-F7E501EA632D
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6C05AD67-A1F8-454C-9056-1AD3142D948D
2017-07-24 1,2:13:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FC90A6C1-0C2A-409A-A8C0-F829B6DE9240
[ThaliCore] Browser.startListening
2017-07-24 12:13:25 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:13:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:13:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
2017-07-24 12:13:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0","generation":0}'
2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0, (syncValue: 6gqpvmWqw0xfaeXKgVDojwnSQhb5nfz5)'
2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9,AD8F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
2017-07-24 12:13:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"21ED5147-420B-4877-B71D-3C4D9F498B8D","generation":0}'
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
2017-07-24 12:13:27 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"65639090-B4AF-4DEF-914A-52E21168A9FB","generation":0}'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already, running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C05AD67-A1F8-454C-9056-1AD3142D948D:0
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5D5997C9-1AFA-49E8-8859-3D3CF8615E,09","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,9D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:C5,9D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C,59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:13:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6gqpvmWqw0xfaeXKgVDojwnSQhb5nfz5","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:13:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6gqpvmWqw0xfaeXKgVDojwnSQhb5nfz5', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:13:32 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 12:13:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 21ED5147-420B-4877-B71D-3C4D9F498B8D (syncValue: IkrB2rWlt9UAJkQJrrkvJWN2wFwIWeUN)'
,2017-07-24 12:13:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:13:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:C59D3ABD-41F1-42F9-B7F0-88F33F9AD8F0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A
[ThaliCore] Advertiser: session connected Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A
[ThaliCore] Session.startOutputStream(with:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3, [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A
[ThaliCore] Session.startOutputStream(with:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A
[Tha,liCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:peer:didChange:) peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:21,ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,1ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A
,[ThaliCore] Session.startOutputStream(with:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 3, 4, 5]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.deinit peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received (6144 bytes):'
2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received (5049 bytes):'
2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received all data: 5NrbuPMB1n,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'
2017-07,-24 12:13:35 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
20,17-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
,[ThaliCore] VirtualSocket.deinit vsID:4 [2, 3, 5]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received (4339 bytes):'
,2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 12:13:35 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-24 12:13:36 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [2, 3]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:21,ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,1ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21ED5147-420B-4877-B71D-3C4D9F498B8D", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:13:37 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IkrB2rWlt9UAJkQJrrkvJWN2wFwIWeUN","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IkrB2rWlt9UAJkQJrrkvJWN2wFwIWeUN', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:13:37 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 65639090-B4AF-4DEF-914A-52E21168A9FB (syncValue: 1ey5QGsYiNgbvxHlLnpvhaDqDDk9XCnC)'
,2017-07-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-24 12:13:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:21ED5147-420B-4877-B71D-3C4D9F498B8D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61792
,2017-07-24 12:13:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1ey5QGsYiNgbvxHlLnpvhaDqDDk9XCnC","error":null,"portNumber":61792}'
,2017-07-24 12:13:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1ey5QGsYiNgbvxHlLnpvhaDqDDk9XCnC', error: 'null', listeningPort: '61792''
,Connecting to the localhost:61792
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
Connecting to the localhost:61792
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
,[ThaliCore] Session.startOutputStream(with:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
Connecting to the localhost:61792
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
,Connected to the localhost:61792
,Connected to the localhost:61792
,Connected to the localhost:61792
,ok 91 correct string length
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 3, 6]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 3, 6, 7]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 3, 6, 7, 8]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 92 correct string length
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 12:13:41 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [2, 3, 6, 8]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:6
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [2, 3, 8]
ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [2, 3]
,ok 96 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
[ThaliCore] Advertiser: session connected Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
,[ThaliCore] Session.session(_:peer:didChange:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
[ThaliCore] Session.startOutputStream(with:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [2, 3, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
[ThaliCore] Session.startOutputStream(with:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
[,ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [2, 3, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
[ThaliCore] Session.startOutputStream(with:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,1 [2, 3, 9, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-24 12:13:51 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:52 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server received all data: 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,F,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'
,2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server received all data: 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,o,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'
2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [2, 3, 10, 11]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-24 12:13:53 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [2, 3, 11]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [2, 3]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:13:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:6C05AD67-A1F8-454C-9056-1AD3142D948D
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:13:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:65639090-B4AF-4DEF-914A-52E21168A9FB
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61792
[ThaliCore] Session.disconnect() p,eer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
,[ThaliCore] Session.deinit peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8B0D7792-3E50-445D-8F43-9F1BFA32553A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6C05AD67-A1F8-454C-9056-1AD3142D948D", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:13:53 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-24 12:13:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:53598C96-6AC0-493D-B665-40226186CD36
,2017-07-24 12:13:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:13:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:13:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:26187934-C455-4945-8564-1D51ABED,97B4
[ThaliCore] Browser.startListening
2017-07-24 12:13:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:13:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:13:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:27D1361A-E08C-4C40-9A05-F4BF7A98811D
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
2017-07-24 12:13:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"65639090-B4AF-4DEF-914A-52E21168A9FB","generation":0}'
2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 65639090-B4AF-4DEF-914A-52E21168A9FB, (syncValue: IGHvxJDuEzpoDaqMP6wQV0O11FygQvRi)'
2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "65639090-B4AF-4DEF-914A-52E2116,8A9FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) fou,nd peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 12:13:54, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5D5997C9-1AFA-49E8-8859-3D3CF8615E09","generation":0}'
2017-07-24 12:13:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:54 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D00BC9A6-5676-4EAE-B32C-0930BC0FF439","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FCE18425-0E52-4D6C,-8613-24BC52DDA992:0
2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
2017-07-24 12:13:55 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FCE18425-0E52-4D6C-8613-24BC52DDA992","generation":0}'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:13:55 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:53598C96-6AC0-493D-B665-40226186CD36:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:65,639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,5639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:65,639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,5639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5D5997C9-1AFA-49E8-8859-3D3CF8615E09:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5D5997C9-1AFA-49E8-8859-3D3CF8615E09", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:65,639090-B4AF-4DEF-914A-52E21168A9FB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,5639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "65639090-B4AF-4DEF-914A-52E21168A9FB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:14:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IGHvxJDuEzpoDaqMP6wQV0O11FygQvRi","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IGHvxJDuEzpoDaqMP6wQV0O11FygQvRi', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:14:03 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D00BC9A6-5676-4EAE-B32C-0930BC0FF439 (syncValue: bWJVbGjdt0TxwoBbHIBnen5,v2l5IPFVo)'
2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D00BC9A6-5676-4EAE-B32C-0930B,C0FF439:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:14:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9AD19499-5E01-459B-843B-D0E4154BBA37
[ThaliCore] Advertiser: session connected Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9AD19499-5E01-459B-843B-D0E4154BBA37 state: notConnected -> connecting
,[ThaliCore] Session.deinit peer:65639090-B4AF-4DEF-914A-52E21168A9FB:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9AD19499-5E01-459B-843B-D0E4154BBA37
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AD19499-5E01-459B-843B-D0E4154BBA37 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9AD19499-5E01-459B-843B-D0E4154BBA37
[ThaliCore] Session.startOutputStream(with:) peer:9AD19499-5E01-459B-843B-D0E4154BBA37
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 3, 12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:12 [2, 3]
,[ThaliCore] Session.session(_:peer:didChange:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61812
,2017-07-24 12:14:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"bWJVbGjdt0TxwoBbHIBnen5v2l5IPFVo","error":null,"portNumber":61812}'
,2017-07-24 12:14:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'bWJVbGjdt0TxwoBbHIBnen5v2l5IPFVo', error: 'null', listeningPort: '61812''
,Connecting to the localhost:61812
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [2, 3, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:61812
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 12:14:06 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
,[ThaliCore] VirtualSocket.deinit vsID:13 [2, 3]
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22
[ThaliCore] Advertiser: session connected Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22
[ThaliCore] Session.startOutputStream(with:) peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [2, 3, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-24 12:14:12 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 12:14:12 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 12:14:12 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-24 12:14:12 - DEBUG testThaliMobileNative: 'Server data flushed'
2017-07-24 12:14:12 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] VirtualSocket.closeS,treams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [2, 3]
,2017-07-24 12:14:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,12:14:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 12:14:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:53598C96-6AC0-493D-B665-4,0226186CD36
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61812
[ThaliCore] Session.disconnect() p,eer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 12:14:12 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
,2017-07-24 12:14:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AD19499-5E01-459B-843B-D0E4154BBA37 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "53598C96-6AC0-493D-B665-40226186CD36", generation: 0)
,# Can shift large amounts of data
,[ThaliCore] Session.deinit peer:F4EA6120-5DE3-4DBC-80E3-BCC6203E4E22
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B315A267-2416-4D99-838E-75A6F373469D
,2017-07-24 12:14:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:14:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:14:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9AE183A7-A964-45CF-B0A2-3F949DC986C2
,[ThaliCore] Browser.startListening
,2017-07-24 12:14:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:14:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:14:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
2017-07-24 12:14:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D00BC9A6-5676-4EAE-B32C-0930BC0FF439","generation":0}'
2017-07-24 12:14:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D00BC9A6-5676-4EAE-B32C-0930BC0FF439, (syncValue: oa4yYnHCoayJqCpEQ15MWli2LoAQN2Kq)'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
2017-07-24 12:14:13 - DEBUG t,haliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConne,ct(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:14:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FCE18425-0E52-4D6C-8613-24BC52DDA992","generation":0}'
,2017-07-24 12:14:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:14:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
2017-07-24 12:14:14 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}'
2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:14 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:14:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B315A267-2416-4D99-838E-75A6F373469D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
2017-07-24 12:14:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"453E9D44-4CC9-41AA-81C6-484AB3F7CC29","generation":0}'
2017-07-24 12:14:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:15 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 12:14:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,0BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FCE18425-0E52-4D6C-8613-24BC52DDA992:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FCE18425-0E52-4D6C-8613-24BC52DDA992", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,0BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,0BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0F68199C-9850-4C75-B33B-6C8AD890D704
[ThaliCore] Advertiser: session connected Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0F68199C-9850-4C75-B33B-6C8AD890D704 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:D0,0BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:D00BC9A6,-5676-4EAE-B32C-0930BC0FF439 error: max retries exceeded
,2017-07-24 12:14:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oa4yYnHCoayJqCpEQ15MWli2LoAQN2Kq","error":"Connection could not be established","portNumber":null}'
,2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oa4yYnHCoayJqCpEQ15MWli2LoAQN2Kq', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:14:24 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8182CC2F-9EF8-4D77-B70E-B56490A7A0EF (syncValue: pgb6jIQ1dF2jTqJlETO1jDiUjfuB3dHv)'
,2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:14:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0F68199C-9850-4C75-B33B-6C8AD890D704
,[ThaliCore] Session.session(_:peer:didChange:) peer:0F68199C-9850-4C75-B33B-6C8AD890D704 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0F68199C-9850-4C75-B33B-6C8AD890D704
[ThaliCore] Session.startOutputStream(with:) peer:0F68199C-9850-4C75-B33B-6C8AD890D704
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 3, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (10524 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (11264 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (8801 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (12785 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received (2452 bytes):'
,2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-24 12:14:26 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:w,ithError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61830
,2017-07-24 12:14:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pgb6jIQ1dF2jTqJlETO1jDiUjfuB3dHv","error":null,"portNumber":61830}'
,2017-07-24 12:14:28 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pgb6jIQ1dF2jTqJlETO1jDiUjfuB3dHv', error: 'null', listeningPort: '61830''
,Connecting to the localhost:61830
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,Connected to the localhost:61830
,2017-07-24 12:14:28 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-24 12:14:28 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [2, 3, 15, 16]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:16
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [2, 3, 15]
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D00BC9A6-5676-4EAE-B32C-0930BC0FF439:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D00BC9A6-5676-4EAE-B32C-0930BC0FF439", generation: 0)
,2017-07-24 12:14:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:B315A267-2416-4D99-838E-75A6F373469D
2017-07-24 12:14:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12,:14:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61830
[ThaliCore] Session.disconnect() p,eer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
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
,[ThaliCore] Session.session(_:peer:didChange:) peer:0F68199C-9850-4C75-B33B-6C8AD890D704 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B315A267-2416-4D99-838E-75A6F373469D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0F68199C-9850-4C75-B33B-6C8AD890D704
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:0F68199C-9850-4C75-B33B-6C8AD890D704
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D3BCC6EA-44FE-4876-A09F-9E60914F514B
[ThaliCore] Browser.startListening
2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:14:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 12:14:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:,errorHandler:) Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D63D92FE-3772-48E1-B182-B4E7084DA19C
2017-07-24 12:14:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpda,teNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:14:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"net,workType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:14:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:453E9D44-4CC9-41AA-81C6-484AB3F7CC29:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "453E9D44-4CC9-41AA-81C6-484AB3F7CC29", generation: 0)
2017-07-24 12:14:38 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"453E9D44-4CC9-41AA-81C6-484AB3F7CC29","generation":0}]'
2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"453E9D44-4CC9-41AA-81C6-484AB3F7CC29","generation":0}'
2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:62A427F4-39CB-44D6-8DAF-F8C47295B57B:0
2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "62A427F4-39CB-44D6-8DAF-F8C47295B57B", generation: 0)
2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}'
2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"62A427F4-39CB-44D6-8DAF-F8C47295B57B","generation":0}]'
,2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"62A427F4-39CB-44D6-8DAF-F8C47295B57B","generation":0}'
2017-07-24 12:14:38 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8182CC2F-9EF8-4D77-B70E-B56490A7A0EF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8182CC2F-9EF8-4D77-B70E-B56490A7A0EF", generation: 0)
2017-07-24 12:14:39 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}]'
2017-07-24 12:14:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8182CC2F-9EF8-4D77-B70E-B56490A7A0EF","generation":0}'
2017-07-24 12:14:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] Br,owser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D63D92FE-3772-48E1-B182-B4E7084DA19C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D63D92FE-3772-48E1-B182-B4E7084DA19C", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D63D92FE-3772-48E1-B182-B4E7084DA19C
2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:53E741C4-352A-40B8-B45F-EAF523C28A69
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "527A085E-844D-459C-B487-DE490C2222DA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:527A085E-844D-459C-B487-DE490C2222DA
ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:527A085E-844D-459C-B487-DE490C2222DA
,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
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
,2017-07-24 12:14:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-24 12:14:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:44 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
2017-07-24 12:14:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 12:14:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
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
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 124 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:7f0edf50-ef3d-4b96-a2fe-748bdcadf441 error: startListeningNotActive
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jFuJEmvPKdmpb3UrpHq80vxibtaERYsU","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CC4B7B43-4468-44A5-AFB4-1272F0464A48
,[ThaliCore] Browser.startListening
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pWcMDLezdqAitVKn05xXkyGEXO5uJ0f0","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:53DB5125-D8EB-4CFB-96E1-0EC17D7CC215
[ThaliCore] Browser.startListening
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
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
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:a77a978c-2251-4a08-abb6-04c064b326f5
,ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:14:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:14:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:14:49 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:14:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8E62C46C-7157-4AC0-8447-5248FCCDBD3C
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:14:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:14:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:943215C8-1BA7-4FE3-893C-D72738EBC9DA
[ThaliCore] Browser.startListening
,2017-07-24 12:14:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:14:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:14:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
2017-07-24 12:14:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B11581D3-CDC4-4C93-A560-BD4A6375972C","generation":0}'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B11581D3-CDC4-4C93-A560-BD4A6375972C, (syncValue: 12TFBheK0eDvuytmyiWpTmcKkvE9PQnc)'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A637,5972C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E62C46C-7157-4AC0-8447-5248FCCDBD3C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:782C8DC0-393C-431F-B729-125C1A096E99:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
2017-07-24 12:14:50 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"782C8DC0-393C-431F-B729-125C1A096E99","generation":0}'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:14:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61837
2017-07-24 12:14:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12TFBheK0eDvuytmyiWpTmcKkvE9PQnc","error":null,"portNumber":61837}'
,2017-07-24 12:14:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '12TFBheK0eDvuytmyiWpTmcKkvE9PQnc', error: 'null', listeningPort: '61837''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0) found active relay
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [2, 3, 15, 17]
2017-07-24 12:14:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectR,esolved: {"syncValue":"QJQgB6YH5kjP2bj9W4BW5jFZVDAvzjy7","error":null,"portNumber":61837}'
ok 144 No error
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0) found active relay
,2017-07-24 12:14:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Ssi4FxEgfSM5RvhLqVW3yJsNDaSV9EBr","error":null,"portNumber":61837}'
ok 147 No error
ok 148 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E
[ThaliCore] Advertiser: session connected Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E
,[ThaliCore] Session.session(_:peer:didChange:) peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E
[ThaliCore] Session.startOutputStream(with:) peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [2, 3, 15, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:15:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:15:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:8E62C46C-7157-4AC0-8447-5248FCCDBD3C
2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12,:,15:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserManager.disconnect peer:B11581D3-CDC4-4C93-A560-BD4A6375972C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61837
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [2, 3, 15, 17]
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:17 [2, 3, 15]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
,[ThaliCore] Session.deinit peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "8E62C46C-7157-4AC0-8447-5248FCCDBD3C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:24CDBEE5-5D87-4EEF-9213-F658E51A5F2E
,# initial peer discovery
,2017-07-24 12:15:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
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
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-24 12:15:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'listening 61841'
ok 149 Should throw
,# teardown
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:05 - DEBUG createNativeListener: 'listening 61843'
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
,2017-07-24 12:15:05 - DEBUG createNativeListener: 'listening 61846'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-07-24 12:15:06 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'listening 61850'
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
2017-07-24 12:15:06 - DEBUG createNativeListener: 'listening 61855'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:06 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-24 12:15:06 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:07 - DEBUG createNativeListener: 'listening 61859'
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-24 12:15:07 - DEBUG createNativeListener: 'listening 61863'
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
2017-07-24 12:15:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:07 - DEBUG createNativeListener: 'Native Server - close'
2017-07-24 12:15:07, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-24 12:15:07 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'listening 61867'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'listening 61871'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-24 12:15:08 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
2017-07-24 12:15:08 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
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
2017-07-24 12:15:10 - DEBUG createNativeListener: 'listening 61923'
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
2017-07-24 12:15:10 - DEBUG createNativeListener: 'listening 61927'
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
2017-07-24 12:15:11 - DEBUG createNativeListener: 'listening 61930'
ok 196 port must be in range
,# teardown
,2017-07-24 12:15:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:11 - DEBUG createNativeListener: 'listening 61931'
ok 197 second start should return same port
,# teardown
,2017-07-24 12:15:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:11 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-24 12:15:12 - DEBUG createNativeListener: 'listening 61933'
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 12:15:12 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
,2017-07-24 12:15:12 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-24 12:15:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-24 12:15:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:12 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-24 12:15:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-24 12:15:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-24 12:15:12 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 61935
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1F103392-5B0F-4BC3-9847-39D5168EED90
[ThaliCore] Browser.startListening
,2017-07-24 12:15:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:15:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:15:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:782C8DC0-393C-431F-B729-125C1A096E99:0
2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B11581D3-CDC4-4C93-A560-BD4A6375972C","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B11581D3-CDC4-4C93-A560-BD4A6375972C (syncValue: LMhfUXS2TnrSYvzBi7lmlLbXYW7WFv36)'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"782C8DC0-393C-431F-B729-125C1A096E99","generation":0}'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA","generation":0}'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7E4D774A-7882-49FA-98A2-2FB6F737A46A","generation":0}'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:13 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B1,1581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:782C8DC0-393C-431F-B729-125C1A096E99:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "782C8DC0-393C-431F-B729-125C1A096E99", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) pee,r:B11581D3-CDC4-4C93-A560-BD4A6375972C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] ,Browser: session notConnected retry count #1 for Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B11581D3-CDC4-4C93-A560-BD4A6375972C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:15:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LMhfUXS2TnrSYvzBi7lmlLbXYW7WFv36","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:15:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LMhfUXS2TnrSYvzBi7lmlLbXYW7WFv36', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:15:19 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:15:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA (syncValue: F4Yfi0rU7donc9lVbQ00N7z,xEC60ob5M)'
2017-07-24 12:15:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D,742FEAA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:15:19 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B11581D3-CDC4-4C93-A560-BD4A6375972C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066
[ThaliCore] Advertiser: session connected Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61946
2017-07-24 12:15:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"F4Yfi0rU7donc9lVbQ00N7zxEC60ob5M",,"error":null,"portNumber":61946}'
2017-07-24 12:15:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'F4Yfi0rU7donc9lVbQ00N7zxEC60ob5M', error: 'null', listeningPort: '61946''
,ok 210 should be equal
,2017-07-24 12:15:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7E4D774A-7882-49FA-98A2-2FB6F737A46A (syncValue: vdEttPSB9JAdK2ZFooiaKyLsjIRuVlEP)'
,2017-07-24 12:15:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066 state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374
[ThaliCore] Advertiser: session connected Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61950
2017-07-24 12:15:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vdEttPSB9JAdK2ZFooiaKyLsjIRuVlEP",,"error":null,"portNumber":61950}'
2017-07-24 12:15:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vdEttPSB9JAdK2ZFooiaKyLsjIRuVlEP', error: 'null', listeningPort: '61950''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374
,[ThaliCore] Session.session(_:peer:didChange:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:15:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:15:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61946
[ThaliCore] Session.disconnect() p,eer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61950
,[ThaliCore] Session.disconnect() peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2F4A4E81-4725-4348-9DB6-439977FBC066 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374
,[ThaliCore] Session.session(_:peer:didChange:) peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "9C47D77D-9ABB-4FDD-AB7A-AF5F6222D9C2", generation: 0)
,[ThaliCore] Session.deinit peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 12:15:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 61952
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:15:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24, 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] Session.deinit peer:278F4659-BFD7-4AA1-9A8F-AB7B5CBFC374
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07
2017-07-24 1,2:15:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:15:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9B88E045-E289-49A1-A686-335529ED42F5
[Tha,l,iCore] Browser.startListening
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:15:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 12:15:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
2017-07-24 12:15:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA","generation":0}'
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA, (syncValue: AvcwVQFCbUfNDF6nf0vuTuPx4yPm2P9i)'
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D74,2FEAA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
2017-07-24 12:15:33, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"7E4D774A-7882-49FA-98A2-2FB6F737A46A","generation":0}'
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:33 - DEBUG, thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 12:15:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0D,DEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0D,DEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:15:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AvcwVQFCbUfNDF6nf0vuTuPx4yPm2P9i","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:15:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AvcwVQFCbUfNDF6nf0vuTuPx4yPm2P9i', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:15:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:15:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7E4D774A-7882-49FA-98A2-2FB6F737A46A (syncValue: CSEtWca6TB4QhhGWI9CWxu3,rprOv31M7)'
2017-07-24 12:15:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7E4D774A-7882-49FA-98A2-2FB6F,737A46A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:15:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 12:15:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:0DDEFBB8-1F1A-41FA-A4D9-BE44D742FEAA:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7E,4D774A-7882-49FA-98A2-2FB6F737A46A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7E4D774A-7882-49FA-98A2-2FB6F737A46A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 12:15:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CSEtWca6TB4QhhGWI9CWxu3rprOv31M7","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 12:15:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CSEtWca6TB4QhhGWI9CWxu3rprOv31M7', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:15:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:15:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 161D7F1C-A29F-4896-AC9A-D46CC97A4B88 (syncValue: 43sylIRG8MTJruvPlYHAEBh,AUGatg6ux)'
2017-07-24 12:15:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:161D7F1C-A29F-4896-AC9A-D46CC,97A4B88:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:15:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:7E4D774A-7882-49FA-98A2-2FB6F737A46A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2
[ThaliCore] Advertiser: session connected Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61968
,2017-07-24 12:15:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"43sylIRG8MTJruvPlYHAEBhAUGatg6ux","error":null,"portNumber":61968}'
,2017-07-24 12:15:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '43sylIRG8MTJruvPlYHAEBhAUGatg6ux', error: 'null', listeningPort: '61968''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-24 12:15:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A7B6BF29-41D3-42E8-899C-68B2A3229814 (syncValue: 5xiTm82AWy3bXtSx321WoP09Ab1qdvK5)'
,2017-07-24 12:15:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A7,B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:61974
,2017-07-24 12:15:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5xiTm82AWy3bXtSx321WoP09Ab1qdvK5","error":null,"portNumber":61974}'
,2017-07-24 12:15:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5xiTm82AWy3bXtSx321WoP09Ab1qdvK5', error: 'null', listeningPort: '61974''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8
[ThaliCore] Session.session(_:peer:didChange:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:15:58 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:15:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D9B3E1DE-3AB4-4E08-AD80-781C08B55D07
2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:15:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88,
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61968
[ThaliCore] Session.disconnect() peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:A7B6BF29-41D3-42E8-899C-68B2A3229814
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:61974
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,2017-07-24 12:15:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:15:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 12:15:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5xiTm82AWy3bXtSx321WoP09Ab1qdvK5","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.deinit peer:E0BDBFF6-6503-47DF-9A21-9C8128FAC6B8
,[ThaliCore] Session.session(_:peer:didChange:) peer:9FC7397B-2F7A-4F06-A1A6-6B3CDB0C5DD2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D9B3E1DE-3AB4-4E08-AD80-781C08B55D07", generation: 0)
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'listening 61978'
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
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'listening 61979'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:492E7C30-677C-4440-B891-29B2EEE1A05D
[ThaliCore] Browser.st,artListening
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
,ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 12:16:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}]'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}'
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
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
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'listening 61980'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "16422896-836D-4515-8898-55043445AE24", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:16422896-836D-4515-8898-55043445AE24
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "16422896-836D-4515-8898-55043445AE24", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:16422896-836D-4515-8898-55043445AE24
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:16422896-836D-4515-8898-55043445AE24
,[ThaliCore] Advertiser.stopAdvertising() peerID:16422896-836D-4515-8898-55043445AE24
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'listening 61983'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-24 12:16:03 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'listening 61984'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0157BC4D-4664-4144-AEE1-E52442CC76A2
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71CF6047-6295-4C49-8B59-219F532C4E4B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:71CF6047-6295-4C49-8B59-219F532C4E4B
,2017-07-24 12:16:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:71CF6047-6295-4C49-8B59-219F532C4E4B
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:16:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'listening 61987'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E43E74C4-4A4B-43CF-AC5A-7668CBBB5F75
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9A9660FC-0EDD-47E4-81BB-352060D0063D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9A9660FC-0EDD-47E4-81BB-352060D0063D
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:9A9660FC-0EDD-47E4-81BB-352060D0063D
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
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'listening 61989'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AD5B7F8A-2FD3-4FB1-97E0-7C33A8C6F8C1
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4EE38675-75EB-48C7-80A9-699742032BD4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4EE38675-75EB-48C7-80A9-699742032BD4
2017-07-24 1,2:16:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4EE38675-75EB-48C7-80A9-699742032BD4
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 is stopped after calling stop
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
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:07 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-24 12:16:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
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
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:08 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:09 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:10 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'listening 61992'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E7F9CB0C-8277-4E41-94AF-C0A8A8A95F98
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:16:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-24 12:16:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'listening 61993'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3F570FDE-D4CE-42DB-8D68-A467CF6846D9", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3F570FDE-D4CE-42DB-8D68-A467CF6846D9
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 12:16:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3F570FDE-D4CE-42DB-8D68-A467CF6846D9
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 274 discoveryActive matches
ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'listening 61995'
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
2017-07-24 12:16:12 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'listening 61996'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ABFDA698-E021-4F72-9D91-7C49934A83ED
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
2017-07-24 12:16:13 - INFO th,aliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "98B7B598-7DE9-4D6C-BEE3-7280F3E37E7E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:98B7B598-7DE9-4D6C-BEE3-7280F3E37E7E
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}]'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}]'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}'
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 277 portNumber equal null
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":true,"generation":0,"portNumber":null}'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:98B7B598-7DE9-4D6C-BEE3-7280F3E37E7E
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,2017-07-24 12:16:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] AdvertiserManager.stopAdvertising()
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
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'listening 61998'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1505D1DA-3E66-48DA-8865-2B30A4F52648
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C4D10B98-F43F-4736-BE2A-F1793B701211
2017-07-24 12:16:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}]'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 161D7F1C-A29F-4896-AC9A-D46CC97A4B88 (syncValue: fWVPHvRGSVQWBDWPJz6v6MusMLTk5yEO)'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C4D10B98-F43F-4736-BE2A-F1793B701211:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
2017-07-24 12:16:14 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}]'
2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:14 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77A703D4-9056-42B9-ABF4-7877E1E90C13:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77A703D4-9056-42B9-ABF4-7877E1E90C13", generation: 0)
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}]'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:14 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:A7B6BF29-41D3-42E8-899C-68B2A3229814:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "A7B6BF29-41D3-42E8-899C-68B2A3229814", generation: 0)
2017-07-24 12:16:16 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}]'
2017-07-24 12:16:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","generation":0}'
,2017-07-24 12:16:16 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:16 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"A7B6BF29-41D3-42E8-899C-68B2A3229814","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,1D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,61D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BDCD7795-8CEE-4F64-A87F-D7D24E9F18D5
[ThaliCore] Advertiser: session connected Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:BDCD7795-8CEE-4F64-A87F-D7D24E9F18D5 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
2017-07-24 12:16:21 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}]'
2017-07-24 12:16:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","generation":0}'
,2017-07-24 12:16:21 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:16:21 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"161D7F1C-A29F-4896-AC9A-D46CC97A4B88","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BDCD7795-8CEE-4F64-A87F-D7D24E9F18D5
,[ThaliCore] Session.session(_:peer:didChange:) peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,1D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,61D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "161D7F1C-A29F-4896-AC9A-D46CC97A4B88", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 12:16:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fWVPHvRGSVQWBDWPJz6v6MusMLTk5yEO","error":"Peer is unavailable","portNumber":null}'
2017-07-24 12:16:22 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolve,d -syncValue: 'fWVPHvRGSVQWBDWPJz6v6MusMLTk5yEO', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:16:22 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:16:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 43207632-8028-448D-889D-1C62D213765D (syncValue: mC2oIKYFicom7zjrXaC3ZwK,h8lhQUAfZ)'
2017-07-24 12:16:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:43207632-8028-448D-889D-1C62D,213765D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:161D7F1C-A29F-4896-AC9A-D46CC97A4B88:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDCD7795-8CEE-4F64-A87F-D7D24E9F18D5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BDCD7795-8CEE-4F64-A87F-D7D24E9F18D5
,[ThaliCore] Session.startOutputStream(with:) peer:BDCD7795-8CEE-4F64-A87F-D7D24E9F18D5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [2, 3, 15, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:43207632-8028-448D-889D-1C62D213765D:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C9F76EBE-64E7-4537-8377-9BC770D5189A
[ThaliCore] Advertiser: session connected Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C9F76EBE-64E7-4537-8377-9BC770D5189A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:43207632-8028-448D-889D-1C62D213765D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:43207632-8028-448D-889D-1C62D213765D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62008
2017-07-24 12:16:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mC2oIKYFicom7zjrXaC3ZwKh8lhQUAfZ","error":null,"portNumber":62008}'
,2017-07-24 12:16:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mC2oIKYFicom7zjrXaC3ZwKh8lhQUAfZ', error: 'null', listeningPort: '62008''
,2017-07-24 12:16:26 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:43207632-8028-448D-889D-1C62D213765D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [2, 3, 15, 19, 20]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:16:26 - DEBUG testUtils: 'Got response data'
2017-07-24 12:16:26 - DEBUG testUtils: 'Got end'
ok 279 response body should match testData
ok 280 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C9F76EBE-64E7-4537-8377-9BC770D5189A
,[ThaliCore] Session.session(_:peer:didChange:) peer:C9F76EBE-64E7-4537-8377-9BC770D5189A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C9F76EBE-64E7-4537-8377-9BC770D5189A
[ThaliCore] Session.startOutputStream(with:) peer:C9F76EBE-64E7-4537-8377-9BC770D5189A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [2, 3, 15, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C4D10B98-F43F-4736-BE2A-F1793B701211
2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 12:16:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-07-24 12:16:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeS,treams() vsID:19
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] Virt,ualSocket.closeStreams() vsID:21
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [2, 3, 15, 20, 21]
[ThaliCore] AdvertiserRela,y.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [2, 3, 15, 20]
,ok 281 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C9F76EBE-64E7-4537-8377-9BC770D5189A state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C9F76EBE-64E7-4537-8377-9BC770D5189,A
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [2, 3, 15]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket e,rror:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserManager.disconnect peer:43207632-8028-448D-889D-1C62D213765D
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62008
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:43207632-8028-448D-889D-1C62D213765D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:43207632-8028-448D-889D-1C62D213765D:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 12:16:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mC2oIKYFicom7zjrXaC3ZwKh8lhQUAfZ","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BDCD7795-8CEE-4F64-A87F-D7D24E9F18D5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C4D10B98-F43F-4736-BE2A-F1793B701211", generation: 0)
,[ThaliCore] Session.deinit peer:C9F76EBE-64E7-4537-8377-9BC770D5189A
,[ThaliCore] Session.deinit peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.deinit
,# can still do HTTP requests between peers with coordinator
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'listening 62011'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:17FDC70A-55FB-4656-AE02-D3FC45735E13
,[ThaliCore] Browser.startListening
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 12:16:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7F5CBA13-5171-4B86-A630-E05A6F334A94
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:16:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 12:16:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
2017-07-24 12:16:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}]'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77A703D4-9056-42B9-ABF4-7877E1E90C13:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77A703D4-9056-42B9-ABF4-7877E1E90C13", generation: 0)
2017-07-24 12:16:30 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 43207632-8028-448D-889D-1C62D213765D (syncValue: hbwQkxwjmVke3UitOie46MrqdhDxEJH8)'
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}]'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}'
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
2017-07-24 12:16:30 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","generation":0}]'
2017-07-24 12:16:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","generation":0}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7F5CBA13-5171-4B86-A630-E05A6F334A94:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7F5CBA13-5171-4B86-A630-E05A6F334A94", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
2017-07-24 12:16:31 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}]'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:31 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:43207632-8028-448D-889D-1C62D213765D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:43,207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,3207632-8028-448D-889D-1C62D213765D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:77A703D4-9056-42B9-ABF4-7877E1E90C13:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "77A703D4-9056-42B9-ABF4-7877E1E90C13", generation: 0)
2017-07-24 12:16:35 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}]'
2017-07-24 12:16:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","generation":0}'
,2017-07-24 12:16:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:35 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"77A703D4-9056-42B9-ABF4-7877E1E90C13","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:43207632-8028-448D-889D-1C62D213765D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:43,207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,3207632-8028-448D-889D-1C62D213765D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:43207632-8028-448D-889D-1C62D213765D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:43,207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,3207632-8028-448D-889D-1C62D213765D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
2017-07-24 12:16:40 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}]'
2017-07-24 12:16:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","generation":0}'
,2017-07-24 12:16:40 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:16:40 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"43207632-8028-448D-889D-1C62D213765D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:43207632-8028-448D-889D-1C62D213765D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:43,207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "43207632-8028-448D-889D-1C62D213765D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:43207632,-8028-448D-889D-1C62D213765D error: max retries exceeded
2017-07-24 12:16:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hbwQkxwjmVke3UitOie46MrqdhDxEJH8","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 12:16:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hbwQkxwjmVke3UitOie46MrqdhDxEJH8', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 12:16:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 12:16:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F5668ED9-ED3C-4A98-9698-3926B9298543 (syncValue: iAlu950,JbqxkvcaTmfj9JCQByj3u4bzv)'
2017-07-24 12:16:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F5668ED9-ED3C,-4A98-9698-3926B9298543:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:43207632-8028-448D-889D-1C62D213765D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62025
,2017-07-24 12:16:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iAlu950JbqxkvcaTmfj9JCQByj3u4bzv","error":null,"portNumber":62025}'
,2017-07-24 12:16:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iAlu950JbqxkvcaTmfj9JCQByj3u4bzv', error: 'null', listeningPort: '62025''
,2017-07-24 12:16:44 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [2, 3, 15, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:16:44 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:16:44 - DEBUG testUtils: 'Got end'
,ok 282 response body should match testData
,ok 283 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7F5CBA13-5171-4B86-A630-E05A6F334A94
,2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:16:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:16:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:47 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:F5668ED9-ED3C-4A98-9698-3926B9298543
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62025
[ThaliCore] VirtualSocket.closeStr,eams() vsID:22
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] Session.disconnect() peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
[ThaliCore] VirtualSocket.closeStreams() vsID:,22
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:22 [2, 3, 15]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
[ThaliCore] B,rowserRelay.deinit
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:16:48 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:16:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'listening 62027'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F34E5D6F-86EF-4E83-9BE3-6C633A0591B3
[ThaliCore] Browser.startListening
,2017-07-24 12:16:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:16:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:16:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:16:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 12:16:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4BA2E6AE-E25A-4688-907A-325BF6EAD4E8 (syncValue: WNwYB61hjyhDUgbPv3RCXdHCGqPu4ZOw)'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","generation":0}]'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","generation":0}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}]'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","generation":0}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:16:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:16:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2E80740-826A-40B4-B83A-A8A5E1CA7D0A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2E80740-826A-40B4-B83A-A8A5E1CA7D0A", generation: 0)
2017-07-24 12:16:50 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","generation":0}]'
2017-07-24 12:16:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","generation":0}'
,2017-07-24 12:16:50 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 12:16:50 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 12:16:50 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"E2E80740-826A-40B4-B83A-A8A5E1CA7D0A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4B,A2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F5668ED9-ED3C-4A98-9698-3926B9298543:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F5668ED9-ED3C-4A98-9698-3926B9298543", generation: 0)
2017-07-24 12:16:52 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","generation":0}]'
2017-07-24 12:16:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","generation":0}'
,2017-07-24 12:16:52 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:52 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"F5668ED9-ED3C-4A98-9698-3926B9298543","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4B,A2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
2017-07-24 12:16:56 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}]'
2017-07-24 12:16:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","generation":0}'
,2017-07-24 12:16:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 12:16:56 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"4BA2E6AE-E25A-4688-907A-325BF6EAD4E8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4B,A2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4BA2E6AE-E25A-4688-907A-325BF6EAD4E8", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 12:16:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WNwYB61hjyhDUgbPv3RCXdHCGqPu4ZOw","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 12:16:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WNwYB61hjyhDUgbPv3RCXdHCGqPu4ZOw', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 12:16:57 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 12:16:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7146B875-BFA5-464A-88ED-B177AA3D7C16 (syncValue: 34wOOGKhFBcvia6RMy1dyu8,Y5bsFHqoE)'
2017-07-24 12:16:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7146B875-BFA5-464A-88ED-B177A,A3D7C16:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4BA2E6AE-E25A-4688-907A-325BF6EAD4E8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:012C3002-26D3-46F6-B870-042527C7A835
[ThaliCore] Advertiser: session connected Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:012C3002-26D3-46F6-B870-042527C7A835 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D2C1EC7-B150-4C83-AD15-672877BC31D0
[ThaliCore] Advertiser: session connected Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2D2C1EC7-B150-4C83-AD15-672877BC31D0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62040
2017-07-24 12:17:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"34wOOGKhFBcvia6RMy1dyu8Y5bsFHqoE",,"error":null,"portNumber":62040}'
2017-07-24 12:17:00 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '34wOOGKhFBcvia6RMy1dyu8Y5bsFHqoE', error: 'null', listeningPort: '62040''
,2017-07-24 12:17:00 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [2, 3, 15, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:17:00 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:17:00 - DEBUG testUtils: 'Got end'
,ok 287 response body should match testData
,ok 288 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:012C3002-26D3-46F6-B870-042527C7A835
,[ThaliCore] Session.session(_:peer:didChange:) peer:012C3002-26D3-46F6-B870-042527C7A835 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:012C3002-26D3-46F6-B870-042527C7A835
,[ThaliCore] Session.startOutputStream(with:) peer:012C3002-26D3-46F6-B870-042527C7A835
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [2, 3, 15, 23, 24]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2D2C1EC7-B150-4C83-AD15-672877BC31D0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D2C1EC7-B150-4C83-AD15-672877BC31D0 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D2C1EC7-B150-4C83-AD15-672877BC31D0
[ThaliCore] Session.startOutputStream(with:) peer:2D2C1EC7-B150-4C83-AD15-672877BC31D0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [2, 3, 15, 23, 24, 25]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 12:17:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 12:17:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 289 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:03 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remot,e peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserManager.,stopAdvertising()
2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsync,SocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler dis,connecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] Session.session(_:peer:didChange:) peer:012C3002-26D3-46F6-B870-042527C7A835 state: connected -> notConnect,ed
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B9D0FED2-8EEB-4D6E-8AC0-E651ACCCA2D4", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] AdvertiserRelay.disconnectNonT,CPSession()
[ThaliCore] Session.disconnect() peer:2D2C1EC7-B150-4C83-AD15-672877BC31D0
,[ThaliCore] Session.deinit peer:2D2C1EC7-B150-4C83-AD15-672877BC31D0
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [2, 3, 15,, 23, 25]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] TCPClient.deinit
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [2, 3, 15, 23]
,2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [2, 3, 15]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserManager.disconnect peer:7146B875-BFA5-464A-88ED-B177AA3D7C16
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62040
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "7146B875-BFA5-464A-88ED-B177AA3D7C16", generation: 0)
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"34wOOGKhFBcvia6RMy1dyu8Y5bsFHqoE","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:7146B875-BFA5-464A-88ED-B177AA3D7C16:0
[ThaliCore] BrowserRelay.deinit
,# will fail bad PSK connection between peers
,ok 290 FIX ME, PLEASE!!!
,# teardown
,ok 291 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 12:17:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 12:17:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 12:17:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-24 12:17:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 292 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:04 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 12:17:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 12:17:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
,2017-07-24 12:17:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7146B875-BFA5-464A-88ED-B177AA3D7C16","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 12:17:05 - DEBUG thaliMobileNativeWrapper: 'listening 62044'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 303 error should be null
,ok 304 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 12:17:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 305 error should be null
,ok 306 error should be null
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
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'listening 62045'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B7D34AFB-2828-4329-9B27-B1AFBA51FA75
[ThaliCore] Browser.startListening
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 310 error should be null
,ok 311 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 312 error should be null
,ok 313 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 314 error should be null
,ok 315 error should be null
,# setup
,ok 316 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'listening 62046'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3ED5DB73-4F66-49E4-85AD-2F89583FD5BB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3ED5DB73-4F66-49E4-85AD-2F89583FD5BB
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 317 error should be null
,ok 318 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3ED5DB73-4F66-49E4-85AD-2F89583FD5BB", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:3ED5DB73-4F66-49E4-85AD-2F89583FD5BB
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 319 error should be null
,ok 320 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3ED5DB73-4F66-49E4-85AD-2F89583FD5BB
[ThaliCore] Advertiser.stopAdvertising() peerID:3ED5DB73-4F66-49E4-85AD-2F89583FD5BB
2017-07-24 12:17:06 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 12:17:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-07-24 12:17:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 321 error should be null
ok 322 error should be null
,# setup
,ok 323 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 12:17:06 - DEBUG thaliMobileNativeWrapper: 'listening 62049'
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
,ok 332 native router should be bad
,# teardown
,ok 333 error should be null
,ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-24 12:17:07 - DEBUG thaliMobileNativeWrapper: 'listening 62050'
ok 336 first call should succeed
ok 337 first call should succeed
ok 338 specific error should be returned
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
ok 343 error should be null
,# setup
,ok 344 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-24 12:17:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 345 error should be null
ok 346 error should be null
,# setup
,ok 347 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-24 12:17:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7d6aef34-4dd6-454e-a755-dcaf88dde486","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 348 should be called once
ok 349 should not have been called more than once
,# teardown
,2017-07-24 12:17:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7d6aef34-4dd6-454e-a755-dcaf88dde486","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 12:17:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c899051-4d58-4c36-baa3-161dddbf6223","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 358 peer should be available
,ok 359 cache contains native peer
,2017-07-24 12:17:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6c899051-4d58-4c36-baa3-161dddbf6223","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 360 peer should be unavailable
,ok 361 peer has been removed from cache
,# teardown
,ok 362 error should be null
ok 363 error should be null
,# setup
,ok 364 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 365 we have not added peer to the cache yet
2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0fa8852a-6b5d-468f-a953-76fb98a88de5","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 366 peer should be available
ok 367 cache contains wifi peer
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0fa8852a-6b5d-468f-a953-76fb98a88de5","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 368 peer should be unavailable
,ok 369 peer has been removed from cache
,# teardown
,ok 370 error should be null
ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ba05169e-551e-41cb-b1ec-c1a976ec9808","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 373 first peer is available
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0214e445-a4a6-4330-80d7-6a0f1d40d981","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 second peer is available
,ok 375 first and second peers are different
,# teardown
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ba05169e-551e-41cb-b1ec-c1a976ec9808","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0214e445-a4a6-4330-80d7-6a0f1d40d981","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 376 error should be null
,ok 377 error should be null
,# setup
,ok 378 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 379 should not be in cache at start
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0f3dba3b-7aa1-4f45-937e-a588e800aa8b","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 380 peer is available
,# teardown
,2017-07-24 12:17:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0f3dba3b-7aa1-4f45-937e-a588e800aa8b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 381 error should be null
,ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-24 12:17:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 384 error should be null
,ok 385 error should be null
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
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2f77a9e-bf2d-4718-82fd-feef8e2eedfd","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 390 peer should be available
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a2f77a9e-bf2d-4718-82fd-feef8e2eedfd","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 391 peer should be available
,ok 392 should store correct generation
,# teardown
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a2f77a9e-bf2d-4718-82fd-feef8e2eedfd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 393 error should be null
,ok 394 error should be null
,# setup
,ok 395 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'listening 62051'
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a3754cd3-a60e-4d62-9699-af2a086e479b","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 396 discovered correct peer
,ok 397 got correct generation
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a3754cd3-a60e-4d62-9699-af2a086e479b","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 398 discovered correct peer
,ok 399 got correct generation
,# teardown
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a3754cd3-a60e-4d62-9699-af2a086e479b","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 12:17:11 - DEBUG thaliMobileNativeWrapper: 'listening 62052'
,2017-07-24 12:17:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c57c26cf-16fb-4943-9a05-df0904863f65","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 403 discovered available peer
,ok 404 peer is available
,# teardown
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c57c26cf-16fb-4943-9a05-df0904863f65","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"09191139-6346-4889-8201-1d9be30ea6bf","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 peer should be available
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"09191139-6346-4889-8201-1d9be30ea6bf","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 409 peer should be unavailable
,ok 410 should be removed from cache
,# teardown
,ok 411 error should be null
,ok 412 error should be null
,# setup
,ok 413 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-24 12:17:12 - DEBUG thaliMobileNativeWrapper: 'listening 62053'
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"66750623-2eb8-4a7e-aedb-00e509f24a25","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 first peer is expected to be available
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1cb3967f-fd4c-473e-b29b-cb94804299b6","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 415 second peer is expected to be available
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1cb3967f-fd4c-473e-b29b-cb94804299b6","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
ok 417 it was wifi peer
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1cb3967f-fd4c-473e-b29b-cb94804299b6","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 418 we found peer again
,ok 419 it was wifi peer
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1cb3967f-fd4c-473e-b29b-cb94804299b6","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 420 peer became unavailable
,ok 421 it was wifi peer
,# teardown
,2017-07-24 12:17:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"66750623-2eb8-4a7e-aedb-00e509f24a25","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 12:17:13 - DEBUG thaliMobileNativeWrapper: 'listening 62054'
2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"865b28aa-fa61-454b-b773-4c4158c9cc70","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 428 first peer is expected to be available
2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c2355f59-068d-4308-a488-20c6cd7a8443","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 429 second peer is expected to be available
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"865b28aa-fa61-454b-b773-4c4158c9cc70","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 430 peer became unavailable
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c2355f59-068d-4308-a488-20c6cd7a8443","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dd0b5bee-f47d-4c56-bb37-e97b2bf58b45","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 441 peer discovered first time does not have new address
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dd0b5bee-f47d-4c56-bb37-e97b2bf58b45","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 442 address has not been changed
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dd0b5bee-f47d-4c56-bb37-e97b2bf58b45","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 443 new port handled correctly
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dd0b5bee-f47d-4c56-bb37-e97b2bf58b45","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 444 new host handled correctly
,2017-07-24 12:17:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"dd0b5bee-f47d-4c56-bb37-e97b2bf58b45","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
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
,ok 450 error should be null
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
ok 461 error should be null
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
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'listening 62055'
2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f8a0cbf1-41cb-4497-b3ba-ec8c3b08e4bb","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
ok 478 Got specific error message
,# teardown
,2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f8a0cbf1-41cb-4497-b3ba-ec8c3b08e4bb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 12:17:16 - DEBUG thaliMobileNativeWrapper: 'listening 62056'
,2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"36364282-a78f-465f-b850-59549055a270","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:36364282-a78f-465f-b850-59549055a270
,ok 482 native wrapper `disconnect` called once
,ok 483 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-24 12:17:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"36364282-a78f-465f-b850-59549055a270","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 12:17:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 487 error should be null
,ok 488 error should be null
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
,ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-24 12:17:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 502 error should be null
,ok 503 error should be null
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
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'listening 62057'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:454154B9-6140-4A3B-B1B2-268BE425296A
,[ThaliCore] Browser.startListening
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f3196490-f4c8-4eda-8330-13755ec319c2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 508 Peer availabilities has one entry for our connection type
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"86540c6f-df6f-4af9-80fe-e5c19fd1af51","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 509 Peer availabilities has one entry for our connection type
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f3196490-f4c8-4eda-8330-13755ec319c2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:19 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"86540c6f-df6f-4af9-80fe-e5c19fd1af51","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 12:17:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 510 No peers
,ok 511 No peers
,ok 512 No peers
,# teardown
,ok 513 error should be null
ok 514 error should be null
,# setup
,ok 515 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-24 12:17:20 - DEBUG thaliMobileNativeWrapper: 'listening 62058'
2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a4d46e52-c2e6-474e-8b8f-1097e09833c6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 516 1
ok 517 2
,2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"26f1461a-2a2c-4f3d-80fd-85ded6652137","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a4d46e52-c2e6-474e-8b8f-1097e09833c6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"26f1461a-2a2c-4f3d-80fd-85ded6652137","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
ok 522 error should be null
,# setup
,ok 523 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'listening 62059'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F894B066-A1FC-4515-99B1-1CE0256E1FEC
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 526 error should be null
ok 527 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F513D266-4360-4A67-8F33-8053B564FDAC
[ThaliCore] Browser.startListening
,2017-07-24 12:17:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 528 error should be null
,ok 529 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}]'
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}'
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:17:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4 (syncValue: 0)'
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}]'
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}'
,2017-07-24 12:17:22 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:17:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F894B066-A1FC-4515-99B1-1CE0256E1FEC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] Advertiser: session connected Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
[ThaliCore] Advertiser: session connected Peer(uuid: "F894B066-A1FC-4515-99B1-1CE0256E1FEC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
,[ThaliCore] Session.session(_:peer:didChange:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] Session.startOutputStream(with:) peer:A5A79C3E-823F-4844-9BBC-C713FFDB589B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [2, 3, 15, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
,[ThaliCore] Session.session(_:peer:didChange:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0 state: connecting -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6749,A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "674,9A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] Session.init(session:identi,fier:connected:notConnected:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.deinit pe,er:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
[ThaliCore] Session.startOutputStream(with:) peer:5138BB49-C82C-45D8-B3E4-2F6BA646ECA8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [2, 3, 15, 26, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:67,49A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62070
2017-07-24 12:17:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":62070}'
,2017-07-24 12:17:38 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4961DB67-3624-4134-A11C-6BF58A47872B (syncValue: 1)'
2017-07-24 12:17:38 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [2, 3, 15, 26, 27, 28]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:17:39 - DEBUG testUtils: 'Got response data'
2017-07-24 12:17:39 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 state: connecting -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4961,DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "496,1DB67-3624-4134-A11C-6BF58A47872B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] Session.init(session:identi,fier:connected:notConnected:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.deinit p,e,er:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:49,61DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62076
2017-07-24 12:17:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":62076,}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [2, 3, 15, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:17:56 - DEBUG testUtils: 'Got response data'
,2017-07-24 12:17:56 - DEBUG testUtils: 'Got end'
,ok 530 received all uuids
,# teardown
,2017-07-24 12:17:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:17:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F894B066-A1FC-4515-99B1-1CE0256E1FEC
,2017-07-24 12:17:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:17:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-24 12:17:56 ,- INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 12:17:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:17:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:17:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" ,UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketD,isconnectHandler removed virtual socket vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket close,d by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Advertis,erRelay.didSocketDisconnectHandler removed virtual socket vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,ok 531 error should be null
ok 532 error should be null
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [2, 3, 15, 27, 28, 29]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:,28
[ThaliCore] VirtualSocket.deinit vsID:27 [2, 3, 15, 28, 29]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
# setup
,[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [2, 3, 15, 29]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket, removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [2, 3, 15]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket e,rror:nil
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
,ok 537 getConnectionType
,ok 538 getActionType
,ok 539 getActionState
,ok 540 getPskIdentity
,ok 541 getPskKey
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
ok 590 enqueue is fine
ok 591 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 592 is an agent
,ok 593 first enqueue is fine
,ok 594 is an agent
,ok 595 second enqueue is fine
,ok 596 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
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
ok 604 enqueue worked
ok 605 is an agent
ok 606 enqueue 2 worked
,ok 607 enqueue is not available when stopped
ok 608 start action is killed
ok 609 killed action is still killed
ok 610 enqueued action when stopped is killed
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
,ok 616 wrong arg type
,ok 617 wrong arg type
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
ok 663 Notification 2 not yet called
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
2017-07-24 12:18:08 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
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
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'listening 62081'
,ok 679 error should be null
,ok 680 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F4A6FA35-7039-4607-8510-571C8926B0EE
[ThaliCore] Browser.startListening
,2017-07-24 12:18:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 12:18:09 - INFO testThaliNotification: 'startListeningForAdvertisements'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}]'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}]'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","generation":0}]'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","generation":0}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9217F548-C7E8-4106-A99F-8C3D222B81B7","generation":0}]'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9217F548-C7E8-4106-A99F-8C3D222B81B7","generation":0}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9217F548-C7E8-4106-A99F-8C3D222B81B7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:18:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9217F548-C7E8-4106-A99F-8C3D222B81B7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4 (syncValue: 2)'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) found active relay
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":62070}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4961DB67-3624-4134-A11C-6BF58A47872B (syncValue: 3)'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) found active relay
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":62076}'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 836E24B5-833B-49F1-B94E-975EDDFDC93D (syncValue: 4)'
,2017-07-24 12:18:11 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [2, 3, 15, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [2, 3, 15, 30, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] VirtualSocket.deinit vsID:31 [2, 3, 15, 30]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 12:18:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 12:18:11 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
[ThaliCore] Advertiser: session connected Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "836E24B5-833B-49F1-B94E-975EDDFDC93D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62086
,2017-07-24 12:18:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":62086}'
,2017-07-24 12:18:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9217F548-C7E8-4106-A99F-8C3D222B81B7 (syncValue: 5)'
2017-07-24 12:18:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [2, 3, 15, 30, 32]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:18:14 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 62086,836E24B5-833B-49F1-B94E-975EDDFDC93D'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [2, 3, 15, 30]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:836E24B5-833B-49F1-B94E-975EDDFDC93D:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [2, 3, 15, 30, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0 state: notConnected -> connecting
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Co,de=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] Browser,Relay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] VirtualSocket.handleEventOnOutputStream streams are closed vsID:33
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
[ThaliCore] VirtualSocket.deinit vsID:33 [2, 3, 15, 30]
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
[ThaliCore] Advertiser: session connected Peer(uuid: "6EE1358B-49C1-44F9-AE2B-8B17E5A90B39", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9217F548-C7E8-4106-A99F-8C3D222B81B7", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62091
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
,2017-07-24 12:18:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":62091}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155 state: connecting -> connected
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4961DB67-3624-4134-A11C-6BF58A47872B (syncValue: 6)'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) found active relay
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":62076}'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4 (syncValue: 7)'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) found active relay
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":62070}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
[ThaliCore] Session.startOutputStream(with:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [2, 3, 15, 30, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [2, 3, 15, 30, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [2, 3, 15, 30, 34, 35, 36]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [2, 3, 15, 30, 34, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [2, 3, 15, 30, 34, 35, 36]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 12:18:17 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 12:18:17 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
[ThaliCore] Session.startOutputStream(with:) peer:24A433EC-908C-42BD-8EC8-ADC70B763155
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [2, 3, 15, 30, 34, 35, 36, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
,[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
[ThaliCore] VirtualSocket.deinit vsID:34 [2, 3, 15, 30, 35, 36, 38]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:18:17 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 62091,9217F548-C7E8-4106-A99F-8C3D222B81B7'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [2, 3, 15, 30, 36, 38]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9217F548-C7E8-4106-A99F-8C3D222B81B7:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [2, 3, 15, 30, 36, 38, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62076
[ThaliCore] Session.disconnect() peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[Thali,Core] TCPListener.deinit
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:38 [2, 3, 15, 30, 36, 39]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:39
,[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:39 [2, 3, 15, 30, 36]
,[ThaliCore] Session.deinit peer:4961DB67-3624-4134-A11C-6BF58A47872B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4961DB67-3624-4134-A11C-6BF58A47872B", generation: 0) relay removed
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}]'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","generation":0}'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:18:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4961DB67-3624-4134-A11C-6BF58A47872B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:18:17 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4 (syncValue: 8)'
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) found active relay
,2017-07-24 12:18:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":62070}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [2, 3, 15, 30, 36, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
[ThaliCore] VirtualSocket.deinit vsID:40 [2, 3, 15, 30, 36]
,2017-07-24 12:18:17 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-24 12:18:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4 (syncValue: 9)'
2017-07-24 12:18:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) found active relay
2017-07-24 12:18:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":62070}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [2, 3, 15, 30, 36, 41]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:41 [2, 3, 15, 30, 36]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 12:18:18 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() state:connec,ted
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62070
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.disconnect() peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[,ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4", generation: 0) relay removed
,2017-07-24 12:18:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}]'
,2017-07-24 12:18:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","generation":0}'
,2017-07-24 12:18:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 12:18:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6749A33F-EC4C-44D3-9AD7-D83F9D71FFE4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:18:18 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
,[ThaliCore] Session.session(_:peer:didChange:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
[ThaliCore] Session.startOutputStream(with:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [2, 3, 15, 30, 36, 42]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
[ThaliCore] Session.startOutputStream(with:) peer:7C91E292-3CF0-47D2-ADE9-B63906DF4EBF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [2, 3, 15, 30, 36, 42, 43]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [2, 3, 15, 30, 36, 43]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:43
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [2, 3, 15, 30, 36]
,ok 681 Peer made successful https requests to all peers
,ok 682 Peer received right amount of https requests
,ok 683 HTTPS server received zero PSK Identities. Count:0
,# teardown
,2017-07-24 12:18:20 - INFO testThaliNotification: 'Participants:3 Peers Replied to us:2 Peers requested to:2'
,2017-07-24 12:18:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"836E24B5-833B-49F1-B94E-975EDDFDC93D","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 12:18:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9217F548-C7E8-4106-A99F-8C3D222B81B7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:6EE1358B-49C1-44F9-AE2B-8B17E5A90B39
,2017-07-24 12:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 12:18:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 12:18:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [2, 3, 15, 36]
[ThaliCore] BrowserRelay.deinit
,2017-07-24 12:18:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 12:18:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 12:18:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
ok 697 correct error message
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
,ok 702 Start after killed
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
ok 731 should be equal
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
ok 775 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 12:18:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 776 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 12:18:49 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 777 action should be resolved with NETWORK_PROBLEM error
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
2017-07-24 12:18:53 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 782 peerDictionary should become empty
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
ok 785 First action failed
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
,# teardown
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
ok 801 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-24 12:19:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 802 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 803 ThaliMobile.StopAdvertisingAndListeningshould be called once
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
,ok 811 should be 200
,ok 812 should be equal
,ok 813 should be equal
,ok 814 (unnamed assert)
,ok 815 no error
,ok 816 should be 204
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
,ok 823 First start and on called correctly
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
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'listening 62152'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7982C450-B190-41BA-9C3F-1E4EBCCE4055
,[ThaliCore] Browser.startListening
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B358F577-9A2C-4F71-9BC2-6A69E0B99696
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"560FF751-846E-4A58-8A52-A4E2B97186CC","generation":0}]'
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"560FF751-846E-4A58-8A52-A4E2B97186CC","generation":0}'
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"560FF751-846E-4A58-8A52-A4E2B97186CC","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:19:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"560FF751-846E-4A58-8A52-A4E2B97186CC","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 560FF751-846E-4A58-8A52-A4E2B97186CC (syncValue: 10)'
,2017-07-24 12:19:10 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"E9586F70-5B36-4872-8956-BF5C544C75F6","generation":0}]'
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"E9586F70-5B36-4872-8956-BF5C544C75F6","generation":0}'
,2017-07-24 12:19:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"E9586F70-5B36-4872-8956-BF5C544C75F6","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 12:19:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"E9586F70-5B36-4872-8956-BF5C544C75F6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] Advertiser: session connected Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B358F577-9A2C-4F71-9BC2-6A69E0B99696:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [2, 3, 15, 36, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "560FF751-846E-4A58-8A52-A4E2B97186CC", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62157
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":62157}'
,2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for E9586F70-5B36-4872-8956-BF5C544C75F6 (syncValue: 11)'
,2017-07-24 12:19:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [2, 3, 15, 36, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:44 [2, 3, 15, 36, 45]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,6 [2, 3, 15, 36, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [2, 3, 15, 36, 46]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [2, 3, 15, 36, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Advertiser: session connected Peer(uuid: "B358F577-9A2C-4F71-9BC2-6A69E0B99696", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [2, 3, 15, 36, 46, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-07-24 12:19:14 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [2, 3, 15, 36, 46, 47, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [2, 3, 15, 36, 46, 47, 48, 49, 50]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] Session.startOutputStream(with:) peer:EDE36A20-3EDF-4903-B9FE-AAFEF64DCF7D
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 53, 54]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:55 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 53, 54, 55]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:53
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 54, 55]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:54
[ThaliCore] VirtualSocket.closeStreams() vsID:54
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] VirtualSocket.deinit vsID:54 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.s,ocketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:19:16 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
,[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:56 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "E9586F70-5B36-4872-8956-BF5C544C75F6", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62172
,2017-07-24 12:19:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":62172}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55, 57]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
[ThaliCore] VirtualSocket.deinit vsID:57 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55, 58]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] Session.session(_:peer:didChange:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55, 58, 59]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:59
[ThaliCore] VirtualSocket.closeStreams() vsID:59
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55, 58]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 12:19:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,0 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55, 58, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55, 58, 60, 61]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 12:19:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55, 58, 60, 61, 62]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:61
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [2, 3, 15, 36, 46, 47, 48, 49, 50, 51, 52, 55, 58, 60, 62]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:46 [2, 3, 15, 36, 47, 48, 49, 50, 51, 52, 55, 58, 60, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
,[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] VirtualSocket.deinit vsID:48 [2, 3, 15, 36, 47, 49, 50, 51, 52, 55, 58, 60, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
[ThaliCore] VirtualSocket.deinit vsID:50 [2, 3, 15, 36, 47, 49, 51, 52, 55, 58, 60, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:64 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 64]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:65 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 64, 65]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:64
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:64
,[ThaliCore] VirtualSocket.deinit vsID:64 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 65]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:560FF751-846E-4A58-8A52-A4E2B97186CC:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:66 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 65, 66]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:67 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 65, 66, 67]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:68 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 65, 66, 67, 68]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 12:19:18 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:66
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:66
,[ThaliCore] VirtualSocket.deinit vsID:66 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 65, 67, 68]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E9586F70-5B36-4872-8956-BF5C544C75F6:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:69 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 65, 67, 68, 69]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:67
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:67
,[ThaliCore] VirtualSocket.deinit vsID:67 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 65, 68, 69]
,2017-07-24 12:19:18 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
[ThaliCore] Session.startOutputStream(with:) peer:41CD5606-68A0-4B38-BB1E-5F21BA470708
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:70 [2, 3, 15, 36, 47, 49, 52, 55, 58, 60, 62, 63, 65, 68, 69, 70]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,60
[ThaliCore] VirtualSocket.deinit vsID:60 [2, 3, 15, 36, 47, 49, 52, 55, 58, 62, 63, 65, 68, 69, 70]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:68
[ThaliCore] VirtualSocket.closeStreams() vsID:68
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:63
[ThaliCore] VirtualSocket.deinit vsID:63 [2, 3, 15, 36, 47, 49, 52, 55, 58, 62, 65, 68, 69, 70]
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:70
[ThaliCore] VirtualSocket.closeStreams() vsID:70
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:68
,[ThaliCore] VirtualSocket.deinit vsID:68 [2, 3, 15, 36, 47, 49, 52, 55, 58, 62, 65, 69, 70]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:70
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:70 [2, 3, 15, 36, 47, 49, 52, 55, 58, 62, 65, 69]
,2017-07-24 12:19:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 12:19:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,2017-07-24 12:19:21 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:47
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] TCPListener.socketDidDis,connect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) soc,ket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [2, 3, 15, 36, 47, 52, 55, 58, 62, 65, 69]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [2, 3, 15, 36, 47, 55, 58, 62, 65, 69]
[ThaliCore] BrowserRelay.didCloseVirtualSocketS,treamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [2, 3, 15, 36, 47, 58, 62, 65, 69]
,2017-07-24 12:19:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 12:19:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,2017-07-24 12:19:21 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:58 [2, 3, 15, 36, 47, 62, 65, 69]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:62
,[ThaliCore] VirtualSocket.deinit vsID:62 [2, 3, 15, 36, 47, 65, 69]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:65
,[ThaliCore] VirtualSocket exited RunLoop vsID:65
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:65 [2, 3, 15, 36, 47, 69]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:69
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:69
,[ThaliCore] VirtualSocket.deinit vsID:69 [2, 3, 15, 36, 47]
,2017-07-24 12:22:10 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-24 12:22:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:22:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:22:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:23:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:23:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:24:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:24:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:25:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:25:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:26:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:26:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:27:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:27:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:28:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:28:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-24 12:29:09 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,nts plugin delay interval'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-24 12:29:09 - INFO Coordi,natedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueu,e and run in order'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-24 12:29:09 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
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
    at SubError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B,-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/bluebird/,js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-24 12:29:09 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-24 12:29:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 860 failed with TimeoutError
,  ---
    operator: fail
  ...
,# teardown
,2017-07-24 12:29:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:29:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:29:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:30:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:30:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:31:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:31:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:32:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:32:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4,A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 12:32:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6,B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 12:32:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E3B91D92-25A8-4A6B-AC6C-0E5D72855DE8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
