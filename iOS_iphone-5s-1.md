#### Test 11335185196ab692_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/6C15328F-D838-4FB3-9AD4-FCA388C4B4F2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/6C15328F-D838-4FB3-9AD4-FCA388C4B4F2/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185196ab692/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:65299"
,(lldb)     command script import "/tmp/6C15328F-D838-4FB3-9AD4-FCA388C4B4F2/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,JXcore Cordova bridge is ready!
JXcore engine is started
,2017-07-13 08:30:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:30:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:30:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:30:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:30:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:30:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
,AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A89E28FD-0CEE-43BA-AC2A-FA110F5C0BE1", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A89E28FD-,0CEE-43BA-AC2A-FA110F5C0BE1
Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) ,peer:3D709AA1-A80F-4C23-90C8-E674B3EDC187
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore,] Browser.init(serviceType:foundPeer:lostPeer:) peer:9ACAB226-7374-4EB4-B37A-DB64FDD67B6C
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "35DE34BD-4BB2-4E3A-954A-5CBBBC343C14", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:35DE34BD-4BB2-4E3A-954A-5CBBBC343C14
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:35DE34BD-4BB2-4E3A-954A-5CBBBC343C14:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "35DE34BD-4BB2-4E3A-954A-5CBBBC343C14", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-13 08:31:00 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.551118969917297
,2017-07-13 08:31:00 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-13 08:31:00 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:35DE34BD-4BB2-4E3A-954A-5CBBBC343C14:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "35DE34BD-4BB2-4E3A-954A-5CBBBC343C14", generation: 0)
,2017-07-13 08:31:03 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-13 08:31:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-13 08:31:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-13 08:31:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-13 08:31:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-13 08:31:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-13 08:31:07 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-13 08:31:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-13 08:31:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-486,5-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-486,5-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-486,5-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-486,5-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-486,5-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-13 08:31:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-13 08:31:43 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-13 08:31:43 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-13 08:31:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-13 08:31:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-13 08:31:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-13 08:31:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-13 08:31:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
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
,ok 32 fourth
,ok 33 second
,ok 34 secondPromise - in then
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
,2017-07-13 08:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-13 08:32:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-13 08:32:02 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-13 08:32:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-13 08:32:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:33F11DB6-BEF5-4B8B-A2D7-60BF3AAE257F
[ThaliCore] Browser.startListening
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-13 08:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
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
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3B39B551-AFE1-4DC6-8E9F-E5EDE49DC850
,[ThaliCore] Browser.startListening
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-13 08:32:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:32:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 08:32:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
2017-07-13 08:32:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:08 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6FD9D801-B35A-41BF-970C-8A1B50C5F5CB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6FD9D801-B35A-41BF-970C-8A1B50C5F5CB
2017-07-13 0,8:32:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:32:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertising,StateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-13 08:32:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "02C7F1B3-FB96-4969-9715-6D8C0AEFB652", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:02C7F1B3-FB96-4969-9715-6D8C0AEFB652
2017-07-13 0,8:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-13 08:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "02C7F1B3-FB96-4969-9715-6D8C0AEFB652", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:02C7F1B3-FB96-4969-9715-6D8C0AEFB652
,2017-07-13 08:32:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:32:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:32:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-13 08:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:21 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-13 08:32:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:32:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "AEF459FD-A12E-4767-8E65-58B69FA8326B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:AEF459FD-A12E-4767-8E65-58B69FA8326B
,2017-07-13 08:32:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BC5CA1C5-9C86-49DE-A797-AC7436831,127
[ThaliCore] Browser.startListening
,2017-07-13 08:32:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:32:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-13 08:32:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AEF459FD-A12E-4767-8E65-58B69FA8326B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AEF459FD-A12E-4767-8E65-58B69FA8326B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'd,iscoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndList,e,ning in teardown
,# setup
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F2E49934-D5B4-44BA-830F-E06FF747D0D3
2017-07-13 0,8:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:38F26A7C-2372-4A66-9872-EC117B984840
,[ThaliCore] Browser.startListening
2017-07-13 08:32:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 08:32:35 - INFO thaliMobile: 'Received state ({"discoveryActive,":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:35 - INFO thaliMobile: 'F,iltered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
,2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"088A3ACD-ECCB-41AB-9B90-34BBEFC162A9","generation":0}'
,2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 088A3ACD-ECCB-41AB-9B90-34BBEFC162A9 (syncValue: vzIFFbAyABdEEuNyzNBrcAbjn35R8uik)'
,2017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0)
[ThaliCore] Session.disconnect() peer:088A3ACD-ECC,B-41AB-9B90-34BBEFC162A9:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
2,017-07-13 08:32:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9687EBC4-01F9-4F14-9B77-F38A65897F0D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F2E49934-D5B4-44BA-830F-E06FF747D0D3:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
,2017-07-13 08:32:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BFAB98DA-9CF3-43B9-91FE-CA3032A13861","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:088A3ACD-ECCB-41AB-9B90-34BBEFC162A9:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "088A3ACD-ECCB-41AB-9B90-34BBEFC162A9", genera,tion: 0)
2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vzIFFbAyABdEEuNyzNBrcAbjn35R8uik","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:32:42 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'vzIFFbAyABdEEuNyzNBrcAbjn35R8uik', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"088A3ACD-ECCB-41AB-9B90-34BBEFC162A9","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"088A3ACD-ECCB-41AB-9B90-34BBEFC162A9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 08:32:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-13 08:32:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9687EBC4-01F9-4F14-9B77-F38A65897F0D (syncValue: rfHyC1NVQh7ngZSfJ6Qmrw2aazx1g9gu)'
,2017-07-13 08:32:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0EA4F31D-AA46-43CB-8BD4-2065FB43608F
[ThaliCore] Advertiser: session connected Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
,[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0EA4F31D-AA46-43CB-8BD4-2065FB43608F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0EA4F31D-AA46-43CB-8BD4-2065FB43608F
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49789
,2017-07-13 08:32:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rfHyC1NVQh7ngZSfJ6Qmrw2aazx1g9gu","error":null,"portNumber":49789}'
2017-07-13 08:32:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'r,fHyC1NVQh7ngZSfJ6Qmrw2aazx1g9gu', error: 'null', listeningPort: '49789''
2017-07-13 08:32:45 - INFO testThaliMobileNative: ''
ok 97 Must have listeningPort
ok 98 listeningPort must be a number
ok 99 listening port should not be 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0EA4F31D-AA46-43CB-8BD4-2065FB43608F state: connecting -> connected
,# teardown
,2017-07-13 08:32:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 08:32:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:32:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:32:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:32:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49789
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:0EA4F31D-AA46-43CB-8BD4-2065FB43608F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F2E49934-D5B4-44BA-830F-E06FF747D0D3", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:0EA4F31D-AA46-43CB-8BD4-2065FB43608F
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:0EA4F31D-AA46-43CB-8BD4-2065FB43608F
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:32:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:32:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0D279F4F-B96C-44A0-AAFA-099C9029E9D0
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:32:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:32:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42D718ED-D232-44C7-8DDC-484B16BA1C84
[ThaliCore] Browser.startListening
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 08:32:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-13 08:32:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BFAB98DA-9CF3-43B9-91FE-CA3032A138,61","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BFAB98DA-9CF3-43B9-91FE-CA3032A13861, (syncValue: PklO7Xdpvtlk1KW2pD6J4YjzUdSlxqlA)'
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0,
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-13 08:32:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9687EBC4-01F9-4F14-9B77-F38A65897F0D","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
2017-07-13 08:32:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D279F4F-B96C-44A0-AAFA-099C9029E9D0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0)
2017-07-13 08:32:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B5FFC2F2-DB79-4AE2-90E5-D9B68505283E","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0)
[ThaliCore] Session.disconnect() peer:BFAB98DA-9CF,3-43B9-91FE-CA3032A13861:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:BFAB98DA-9CF3-43B9-91FE-CA3032A13861:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "BFAB98DA-9CF3-43B9-91FE-CA3032A13861", genera,tion: 0)
2017-07-13 08:32:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PklO7Xdpvtlk1KW2pD6J4YjzUdSlxqlA","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:32:54 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'PklO7Xdpvtlk1KW2pD6J4YjzUdSlxqlA', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:32:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"BFAB98DA-9CF3-43B9-91FE-CA3032A13861","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:32:54 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,08:32:54 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"BFAB98DA-9CF3-43B9-91FE-CA3032A13861","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:32:54 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:32:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9687EBC4-01F9-4F14-9B77-F38A65897F0D (syncValue: q6ATMQ0,DtdZiJsSppGINhjZH4weRcqm4)'
,2017-07-13 08:32:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0) new relay
[ThaliCore] Browser.invite,ToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0)
[ThaliCore] Session.disconnect() peer:9687EBC4-01F,9-4F14-9B77-F38A65897F0D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:9687EBC4-01F9-4F14-9B77-F38A65897F0D:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "9687EBC4-01F9-4F14-9B77-F38A65897F0D", genera,tion: 0)
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"q6ATMQ0DtdZiJsSppGINhjZH4weRcqm4","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:32:59 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'q6ATMQ0DtdZiJsSppGINhjZH4weRcqm4', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"9687EBC4-01F9-4F14-9B77-F38A65897F0D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 08:32:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9687EBC4-01F9-4F14-9B77-F38A65897F0D","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:32:59 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:32:59 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:32:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 61756926-9537-4B4F-AF8E-72C7D7AF849C (syncValue: dqKfTx8,sDPON4vxYLYswgI2q6srvATEq)'
2017-07-13 08:32:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124
[ThaliCore] Advertiser: session connected Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124
,[ThaliCore] Session.session(_:peer:didChange:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49797
,2017-07-13 08:33:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dqKfTx8sDPON4vxYLYswgI2q6srvATEq","error":null,"portNumber":49797}'
2017-07-13 08:33:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'd,qKfTx8sDPON4vxYLYswgI2q6srvATEq', error: 'null', listeningPort: '49797''
,Connecting to the localhost:49797
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124 state: connecting -> connected
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
,Connected to the localhost:49797
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124
[ThaliCore] Session.startOutputStream(with:) peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [1, 2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-13 08:33:02 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 [2]
,ok 104 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client discon,nected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,# teardown
,2017-07-13 08:33:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 106 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:61756926-9537-4B4F-AF8E-72C7D7AF849C
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49797
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] BrowserRel,ay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "0D279F4F-B96C-44A0-AAFA-099C9029E9D0", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:6D36D22C-02F7-4FC8-A4F8-7E90F96EA124
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C
,2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D8350784-49FC-4363-B5DA-9D3049A4F3FF
[ThaliCore] Browser.startListening
2017-07-13 08:33:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0)
2017-07-13 08:33:04 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B5FFC2F2-DB79-4AE2-90E5-D9B68505283E","generation":0}'
2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B5FFC2F2-DB79-4AE2-90E5-D9B68505283E, (syncValue: kySRr5vHIAVX15VKgtzrZZ8exnBBPOJM)'
2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-,D9B68505283E", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", gene,ration: 0)
,2017-07-13 08:33:04 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
2017-07-13 08:33:05 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CBE4BA45-6080-444B-B5A9-545B9189CA71","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A385ACA9-6BE4-4961-9C6A-7F8665F19C7C:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0)
,2017-07-13 08:33:05 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"08B6D133-C3D4-4338-B019-A18C4389675A","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0)
[ThaliCore] Session.disconnect() peer:B5FFC2F2-DB7,9-4AE2-90E5-D9B68505283E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:B5FFC2F2-DB79-4AE2-90E5-D9B68505283E:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "B5FFC2F2-DB79-4AE2-90E5-D9B68505283E", genera,tion: 0)
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kySRr5vHIAVX15VKgtzrZZ8exnBBPOJM","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'kySRr5vHIAVX15VKgtzrZZ8exnBBPOJM', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"B5FFC2F2-DB79-4AE2-90E5-D9B68505283E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 08:33:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B5FFC2F2-DB79-4AE2-90E5-D9B68505283E","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:33:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 61756926-9537-4B4F-AF8E-72C7D7AF849C (syncValue: ldBGkH9,eevAU67pioONZQVTFNUdxHyQp)'
2017-07-13 08:33:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849,C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", genera,tion: 0)
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ldBGkH9eevAU67pioONZQVTFNUdxHyQp","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'ldBGkH9eevAU67pioONZQVTFNUdxHyQp', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdent,ifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:78F6A44B-E96D-4449-B257-3BC989A80123
[Thal,iCore] Advertiser: session connected Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:78F6A44B-E96D-4449-B257-3BC989A80123 state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.,init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","peerAvailable":true,"port,Number":null,"recreated":true}'
2017-07-13 08:33:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 08:33:15 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Conne,ction could not be established''
,2017-07-13 08:33:15 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CBE4BA45-6080-444B-B5A9-545B9189CA71 (syncValue: nfK2NI0Wcajv4QI1IBcYqBprcmnIqQZq)'
,2017-07-13 08:33:15 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5
[ThaliCore] Advertiser: session connected Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:78F6A44B-E96D-4449-B257-3BC989A80123
,[ThaliCore] Session.session(_:peer:didChange:) peer:78F6A44B-E96D-4449-B257-3BC989A80123 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:78F6A44B-E96D-4449-B257-3BC989A80123
,[ThaliCore] Session.startOutputStream(with:) peer:78F6A44B-E96D-4449-B257-3BC989A80123
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:78F6A44B-E96D-4449-B257-3BC989A80123
[ThaliCore] Session.startOutputStream(with:) peer:78F6A44B-E96D-4449-B257-3BC989A80123
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:78F6A44B-E96D-4449-B257-3BC989A80123
[ThaliCore] Session.startOutputStream(with:) peer:78F6A44B-E96D-4449-B257-3BC989A80123
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5
,[ThaliCore] Session.startOutputStream(with:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received all data: CU9dXnQPKSqzgkx4pyvPyfLo1h7UMNQxocVxcMXJHxP5DZXU4WMBkWotVuDnD46aEbivFwFfOjbFZZqmimN2BYNuds8x0PM2yy13InBFAmpWyd5PnLyfGWFphDfIDTWMzX2qG2SoC3i3fhdZ2sgfU3sy6kMAwC3hx8iT1sBL2TFS56AchM,hD4KeYcsf7yIwNXId1dqVpXaysr0NO3OuZwM48A5mFlePaKHz0WQhPQA3nYorw47W3DaM02RFDpXoKEqNAFRn7j77dgFwcyS6nIay6hZL7NjYt4FpyQCNoO4rvF4lmc7uK4chpPaRTpeMTxhDFstQ6Tnf7ZUhFFBWh1Pk2JW42iVrDWcg9dFQ54iIElkh3DMfOJQRIi3jCpzvab1luUyZcBPLL9Z2c9fCCE54ENCasSIG8ilUULPpPlvO9stFOnA,704m9cAAazlxfwckAShVC28J4Nnv7rclEK21IBUvYq7D93cLeoVxSLR2mOntu5L4hyY6OgX32hr9B0XKv9Ix5hj7kyNwyPwqka5ZejmljtMUXneXp0Wx3rqJVnaAWSxh8z2Vr6Bi7JEY45KF08o5Oc6xxmYoMrBCLTZWQzNid5V6812OKdVdsomkvXrVpxGfUp38AKu7LNTnRSSAG7yeiSLX2YKBZ3pSZlcV5jyjjgtAum8IfCeW4FoRHn63Q7R0,tri4THFrZcvxqsGJdYzSj7okcRmDL3XLEQ9JBY5WpSJfdAIOp6cvcrYy6jFQQenpPxR9MBUJGdTx3J70jHjsczdxoqCnxQzDaioyCSxSW4eV9ocNm9COJRNhyrdaLdXTE1gylxoCSNAty1y4h5hrL4cQimFNZkJGZoAddIzMTtehkS122vk8eBEfAfoODCgn4LfySvC62yBgoXXQ6MMhjpgv423ALi1bQ5G9ximZUbIoaKGyIhZmO5g2mCfUQN0f,DMXQwetHR0q6ZhLlHclSiG8xo4dRsAeEQrAppT95EghUnZXNuL4VO4uMPqQJD9p4Jsk3Dtt2oAEMVFSPZXX9oXYZrvi57BJemOwPNvYhCaObbORh4aAM3DmU9myjjo4KKNJBwrY44o0d2kMbCSoZTMJ53DwwmNUy7fCrc9Np1M2kzjD2IcaXN1cSn1q83n7fPZekY6vNJnMJqj1IxlXYgz0ooLwVviLrYsk6aa35eHslvaqGMF9B6umcL65QWwcv,IbT5tjUGmILSLhkgNVfmLRTm2Pv31cp4m8T0g1TGnZ7X1gyCQf3e0554pGJvztT63B3rMudLP7DMSSaU0Ia7p5epx8N1jaH5fkiGuTumrdrBmQVrmKFWjwicn0lxJRBpu1TlbS4lD1RttXq0Ct5fmRrGowFEljAqibzBPidhhoKpiwBWQaDSgijoptkfq8jMTXo455dBND1zkU8v3BvGQGwA8vGaWLTXzGQtwc8MQIOc2H1y6mpCJFnYQqqcBKxk,NFKrMkihQJT5oVvyjPwirGkQN2pzIvw6HoxFcs0ZwtA17AKr56qWfdrHAbKOb2CmbFVN8Atq7PgzijzHtaCrCugWDPkEZ0BlWFZIanK3EhqRlPRH2eeCEdNWvhjVc33Yiit7YCIZ3rdZA5Y0ZhuA34fXzIpIKSXqo2vCxw2ecKRRMPN6C4xau46NN82D7za4eA9LJx7PcPvDXJsu9XiPgAsJyZSd2wO3DcYABQCIFRodYw9Pl52MLgb357ptSO9c,COGJEchGJMmSJsoiEF67cDtYFFwK9i6wAODnjrpSd53H5eDn4dPHHc9qgFnjnUzoadjAmjKWMyObXxVCpZtnKSCaFaMgmMDHRYPVL2KzybwWvCQ7e6cqhDft692Oblh0ObF1YpisQMl8DEPdz8p2Hu9TaIvj3xapIlw2oNrWEWx1y9YRT11IrcVkdkVSJ0UCKSCT2Bn09GkL1yy4e1X5MqayfKwHMR7DRyiTsYksG9vFlB6TuHq4MRgRLynUWLYB,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5
[ThaliCore] Session.startOutputStream(with:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,gvh17b4wualgJSbVDCknsKEDuVclkwA52yT5KCXqr1QEgbRHnHHKencjwojFVnmvwndXP1hpeYZspwyROxjBr2MYe5aEScBGdNpV0HaXRfmOxNaUN90ODl9owaykAcxUxIfr8Oq3qTTVDRCN58eE1DUuj9NXQusqjsVie6LiZFavz5DjVzdge5xTN9IqgqAy0ELqVidy4GYKXn20EEvkurdgVmIjRinqM0cstoCv0m2V9Vtf7lklXnzml2mDiMA7,tRLAsEqQtiudS3PUGRuXOGbAEoDfiDVffNhvEAi7jmLXrgjBLcTdGZbB3Yswxo9KdlsJRfGF1OAkyEfql1YGEfARRLtqSlls6m2MV2LhPa7S8QfbMrx0DeKGHRUD8BVCOmlUyx60Ntv6HzpQ01dAUvwP6yuKQUd2zajqWkmXS1jSywWQP8T0ERJ8FyS2lOZ08giqFikuK5zZmorneCnVUyvWd1fbNAlQxq2ByJtU7WU7HRPG5z3OzKoT79UcCMUa,2r3pKmw84fKImzPevsNx7cOseGJiodQUbrp2TdgpSBWsY1zZB6eVX67r95lcBoLveAEVcZ9CQFkm7LtArMwlfhsndxzFsIneocgcJrIluUEANMONkvvmTubyYIbbheW5onVXSYaDw3OwOts38FrsBgxBGfuvn1dgpE5U3Zw9RJ8OttDAtcw3cRRVmjncIllihOlH4dWAPPskHtCUysnBkVzQIFU9G5vGED95dmcZcF6wnSEaxsBEGOyVgqkSDBr1,ZLGz2S4aNwoFIyQE0Vgi4Lkbfgp3wFJwVhsVDxKIfFqLQT41jOIxbNHAsvpbeS7JCanrIgC4UxY99oXmMf1eH1z2WirTyvVrdpiW2C6cR4qDa0URmhD6IY25GjLsdAdpXiL0I3HfDZLJjNTzzmMlYntwaSxg8tSuchXpFL8W6piYz6sM5SspEiQu0ua28aVFYE70mZ6sZ6dV9zMLCWJN9iBCrUrelTfM34ZQGcREMZcaDI9FvTXmf8RLkqp30b8,L,V2oXKVuYqot1OMIUPEfiMsSIJ2g6gXiuBx2liTZs8jtYTVqaBYDPTzspc0vJDG3lGygueq9RuM75WW2q9JDHvHUVaqSElFgMN9D6nfCcm5POxc5FiB3H5olEq3jxTE7spfPFPMRJpeQuGkfEITSrNLRamA7qwfZcYJ8c4GoOZQKDkAcyJfswLMriAWykSFcTm3heR0UXxGQH2lyVcjjg15uy7Lbb3Fq7rlkqrVq0Iv6WyGaOmgB7zwrLCUxfv3xR,IHk0MQQ1CrNufgJh7vrj0IlKyWKZOGpqyz0oWPidau2gcluBf9QEqU3Vv7881bWwPIcNAbUtzupDd5iKqzyhKi8heBXTE0VLIdEm27jRl8J0lXCK2BbISSxuWPjl37wDdi1etKanMvQi6WMCoMhWzONlairHDe1vwpO19FMIIhbjfbMd0zrYUByJpVGUN0IwXIkzzzVBEnoN8aogZN7WIe6y1ZRxya9cwfcHDJtkhCDIUdxNQ1LeQ17JRwlPOdoo,F37q7fAiR7kHCP3dUCGwRwtDk80bvctdnLwpR4X4J6Qk5AV0KtpRCk572WtbGE2EhyYwfcZnTROW3Pr5mTW7WhoT5LPb5DloPh8p4KMLj5csu3Q76r6rJa4TvuxErBeAnDnnWk3hIwLD00BYYDAnprLTBXCA3iPyFILYxzxI6NcOPmz1YaAYnqOK6Zv0FmppfubCOK8XKedwvauf8gFo3OaHy344SfLdWanXQyIPU8J181TvMKUFMAUGNOUvyMuS,GKDWnZMqI4yeARZ1DxHKZFtvwcpFCb8ULOZrYaUUrBEjLFfAIVX7e73hYYonDGugvXhhKWY4qOgYDxZdqKUXzmJlWwIex8Opq3CzgS4JkGM27KYliwIgl6HqRG5YZUjV92TDDGybIIWYgXaQ6D6uSmr41nPi18oO6RX5HjckRHdxrQnWRiqFXGSSuQuLWMZhEabWSsWMiV5Vol2zUC9P6WF8nhr5KsTp8RgouN56Q4MFU2gH0kzpcXk9oAprKIch,aasjtQRLCplU1GwWGKOV2oMm4WtQVgXyLq5DQwjfx9VNwgpcLCG3rM1ungWS1EA6qSVRKEGD50ZtRPh3DAqPZ6ZcrMtPmqn0pg3GiseLz7Vok9Y9YnLO2tGvSyl5IJnqkH2rPMwFoUmUVaPwLIxAUUWcPSdqDMitfCSc7yb5OiPiPikIQ5yJEoP9MiLwWmzy4XDIaNSmpTf4EmibAuZd74eUlnKy57FrGaINNN3RURPudEAwDxtxv8ttvAbCduiV,7so5a02zSQnApZa1emjePBXHFgnAwoHV60UG1s2uO7FDVQt84IkHHYAAYS8ecbpWwIi6pbOcZZRWiOEyxu3IhxpQRuUIDSwwzdHdjQYLBAGB1qK6AaF4IqWtZjAHJOJLm4mOfDM7khKV0fM9pBqPmCMoPecqpLgYKfuqqbrGQkC559N72wfxq7Pkmi7yk4IVHpGhDJ3Gzbhhbp36aMoR6ObfoFXWov3zTJPvZWmw196yPrFhwBgtx3Z4qoW3PtGM,iZkxcRYDrfZICOBQQDVxhw6vUAliJVcdsTfwbCyaBkliFrFekp2eDvD3GC7McAFbZJmOgm6SkqpbCRgWh25nhpuM1fdcb81GaXGxK7TRE6JskHHYJEE42cJIuRFx0DNIOxef10U9lfL44GjS8XjTbighuA9G50Z3ghTYHeR6LlPYyQP6tfVHlYgI9gwwD2UpPdZqBfb9Xv6WpamfHqqwvXidFO92OIGhhWVsBDXNblrHvzDUVlCl1UO4D70DUYxk,rd0LIvmYViTzbbFXygoHpBLOPGR2uhJbFLoCd92jm5XiAYaOXCtYWMA3OFlO0aS5x5gfuocNrxP6XTsdcbpbwdBPgbleDkeRVGM2Lsl97us6Wt8jKNdE7xNgie96RF9nKZ0Sahhm6kcQT3CkOge0LBnsFD4peMsiaIakKlNT7BAqnNA1U5MKA6rt3aGGiQwj08Jn4n7tOya0np7M8l3BIXoWkOArbXCxipYF7p7MshpAuycD3RzJOzEbdOsSUBc4,7SsAX10OzHmBFXgGm97l9O9OIcYXtmcUi8ByNPX9MSanG3znAMq0NmKlXFttDfgxUPd3rPR7XWzky00rKc6fizqpKQzGDsEWKe8mA5CMld5yXuyFyUp8pl6XifaHrM3QNhLUKiYdbrsRaYBf00cwMzAsvk0ETg7ygdFsopk0Ye3kfwnKIW963UFIwoAEc1aGzBH3u5hv4NLfCDG6B4mfRp6xbBOoLfHhg0W7MJlForIZ5sNgjXiUjMV1CAJIYePq,R0zs0QM4Nom2Mjk0cIH83fOY3LhxvO3kp1Kf9kS3hrwLghRYXAiJyck0nympRu8jXxXEFmsi1fBZqy8NBrzIkyDr4CMTNmYVrFI7zkT7H8xUNsRoZ6on5BNYgB3bUxD7GdJQvR25iLjpox72rA1FlkpVJQt6UjA4uNA7o7UT0ErSZOT0AxSmP2Eg05J7PkwZaQf9e0E7NMxywwdSIMdCqwkevCjlqwkh6ypQQbT0emHXR2slG1NEWuIuq9PMUlbA,Wez6JZd7qnwb3Dr86agP3FZu135bjXDSEz4Sbirh9jibCwUunT0QTcKTL8Tg7WiDFQ3mFcXh1x3DAr04f4KL5M48SLRAQ6cjyNTvt8wkvexdEa1yjFo7Y33mbRHIWYBCEdVU08R8ivkJBg51wyV0XMdro3E47imS3jG6EkYJU8EuXVAWjPM1odcrrZdPW15kOTqIt9lkWORApoPKxEdnos8IiTTVIbkCSYPgvHyspFTOTeJuPv3Z1eys4hHEpxi1,ekQ6zZNTxv7hnvtyoRVGwuC6UnBl8XvqSAj1vyJBQcTRDED3fAZSrnTyaEwkH9Vg9996ZXDs5S4ufVg2RlmETSyIAKlTMk3G1sCT4ncmfq0UdOY3Gcda0Mqq4hqGBehUbSYIoHv3FDooXuI56UT86b0mkivtTSrzV6CPlQdZDh7mKwFrJ02YLAvmQuketAi4Z9xBKN53PV32VM0fv3A3tVPraLzAB08WDJimMjwXctEBuZW0iS5c07TzZ3lczXgG,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5
[ThaliCore] Session.startOutputStream(with:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 4, 5, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,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'
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5, 6, 7, 8]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4,
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socke,tDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5,
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [4, 6, 7, 8]
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (2048 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (2332 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received (2149 bytes):'
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server received all data: zDROlMFvqOWPbJYA8yJSFMqy2kUUufS93is3NgkYSsNrHXnEWnU5W7VGl0y6EXvZ632s4gmjoqWFcgg3AxCvOBX4u1iE4,xqzTPXWhL2W3U2TEg6FvgyAjg75G4IXZKKZ5CUfGIHAoKebsEtCK9mTq9d5Vg0vU2ULY7mSsohjGTYt5bAMYzjl6pNh3bzbR0ENM3PVCqFEvlLDvCmIGV9XDXX46bvqVRxEpYMR4LIrqSRKeQdDb622Sceg6i1EvFn0RkhQCPb5vYswDBrPxYuQ053ZqdlHj6pbbb4Ll0SW3uTlsKo3tuRoUj4vgq7dNWxquzhwN0ZPOVbuqpPUAtCMRCAT6pFK9,bLm6aaBG5bo9vadk5c6sNhSu7ktAf2pGhxUlQGCHLSkd328H2GhdNpZsoOg5PJqNPLL33HGhQZGygSBTd6uBYv2tCozbrNZDuzJjr0XPlrU7Ez71lEgFuaf8JLqwtIwvfWOHaLmRoSAF48WOBP421RE08iyYVFepgJ6fiGwKmwrPuodo9YoFHXgWqUQdaRE3B4bp2bafn3o5UUpnhv7acS56Awvv2IkuuJhxVYwmCjjKwfxllM9ymTV3pIemhLVS,quRFgJmHVC9ZhoqG92xtwAy9TRNZIYvUNejjUoOfYq8yf570956U34jDUIw8h2iEClbJGqKW8BIIlR9sklKn83RqTdSGczZ5R7kBx9B1kMhCE7BDauoFzBvWxntmeZRTxUwSZlffoPbJyHHa7hrF2gctAFI4DjAsKUkpyODAsimTF0nEjVY7Ni9kNV8tNQReeIXuh7JdGzZZfVmRtlDhJxrL17ihbNssVRnYjuaN43cxyfg3WJlfpwoAXnPpcR6,HFBV5J6l3mwL4J0xYCZDPEpkUBNoDLdHV5FuwBTvoc9eSDgwFUH2pt5XIgd2UNOflHPOKMaxUcq5RMk7fcTDH43HA1qJZKS587KLmDDi4nuPcNymHuTqg9VuXRIdiLobAK00tQrOuKjmGGgR88bDaLP8ttUU0HgbT5mmyqFWXsa24hyHWdPT2RLpRY9uzt5QuR399HkxrQuU4qwkAXbh9m4wLJn2xx82qGXBeqVe64lauRNSMYx6YbId8nrbN63K,9JoXRhvY9nJkWCWqQqjYXweKtbsjpqrUQMkWXGmsTnbcuFImArCeHUByTvJiiQsQmSkAl7XGjJZc15eZvxaABE2zEpaDy1GRPYe4WiIgmrN4CbZToeS2GhIANA9IPiNBpqzfIt9Mki2jUidOC3eOXArsvsD9utNOhzSjkfrDnZ1gaB69uHaRLQmAYzzMH2zEWXNCEYoQdDl6HwNUjzcXvJ4TPO3UZa5yoLDPMcwVjOmMRFju7VhdS0Fu2SLyST3X,GPRRBb4ve22W5W83VfFSgxwqT810F9WNnknIuOkhBxyP4kXwjSnYoZZVDriRhJAUf7NZYIc1ncfpeBjUFbmJG8oMDUq5MHM9VmrTGnDainIKW1iGn1U1X67Fokv6gEg0LUJAZ8MMd68VZ137qncwAOUnBdJpFRo65rp3ugAXQ4c5inUHNBOyq3Zc1P8Yn40yIch9gCcGXV04GkAuanD3ICXbixUu3SlGbW2EFoXWKzicvOItXwC51z3CfuIhBkpo,322mHmZfeTXS3NbeWRCeWWArgfSX1C678LBDSwslqOVSCSBUVSxyOnaRsxe1Va5R12aTHihRS7X7k1nmOT7N5bfeGadfF8tAIIwHgsJe6EKKFelYd2nxbUexQSGXgP3NJsG9yO1UJeLRoJJMuEOcW5d5M4GHeznrA9lCWFXOclcyc1QzKlMe2zLN1CFmuoZnbinROqrBk1yMW9bkMwg88esHCMo78lJKbgpQjEJ4HSvL9lcdR7a98U2dQrSdRzqn,SqlQ8GsoY46CSRZodEO0kT6lvej98lUdarQJybUpbXaA9NkYyxgwmcmex4msWTdovOfinGIgM2OCZpxXDqiKl27G7pAFCosWhFtnfb3KcVmPKLaE8EmlVdW91JouBam6kNiFF1SDq5asfu4bTqeMMg6t2eIQNQk2bGKZcyZzEx312jttAF4UXIgPENPZKpZD9YpNKcNzp8T2UMVBmRtSsnIizVO5n3pXlJ136Bduo4ThUuPece9U6CmUpxSoskrh,jnhzJQC3bIHVi0K340A5JTLER7rPvKOAUBsJjV7xtgvNxWjy75SYNM8yiL0LShfJtgEw7Gd6HuYSOewcRLLGaQOJRPbeufBCYzkrpmohkIXuH1n3cf1Zp3sueqQlhCEbYf2AEjqARK7RfgA9sD1pI9YMzdO5PGJSvlCpOpBMMTP6cFHN5ia5vtc9lAiA7A7vwpaOebm0ozO0szpvstYmJYDVSk91XiGD3BPDjuaQ73DnvcLSGCNZQwRgu2ALS9Ur,CsmqILZe2Nf74cnMZCK4kCnziRhPkm8IgF0yyIqQTObw9czknTrXeycj4gQUbpaw18vVSCYzMxewssTbPHC6seVfIPZZkX5lZLPKx5jRnP6ZnrngbVR9IHdvrrdriDkSrjKFFXORd5LEvomEg7F1e4yTfrvl47aj46skJUZUEkTfPm5gmcZdgTIgp5rLKpiFwxHeeRe4AR0JNs3jhb7YPWcPdShVtsWykrSjyvJ4J5d0ciWkYOd5vH81UDFHRH3G,tj9DyjcBIb3T6fs3CDAV71jFPxuFh3cAbTPpWxLzIGmhIhKcLEcgeQz33ROWTGdOb4foHbMoU31pVsGHr4OYbHD76CknPpgXYv451jKNtqsJ68cU6tBmVaNNCOKM3Q2LxLtqxTkLYYVZ2LNfrBk7QwfDxXmJVDlbukfFRUSvEEdqlnVHCDt3wL9fXVouT59VYxTNol2J10KLNBPAjqdhXjDK44YM5iQ86f9ESnqVZeZvZnKMlToG5mUOq2Icx8nQ,2DlAG9tMZXKJZd0W7dQ6TcPfPk4HOhanmEefeW2qHR9E0jgljkvdzGq4msWGLpN6xag35sJXHs2JcHhZhQgRrwy2MisUazRzo4pPu7T0yGao0bd56eHjPY4xzjz3niQ5dTVzztu8aacxJxew7hDGSkPQspsezGcMCpbgNpCNPOHcBBe9fMqj0jWFUg6ewjv7o984XLDMOacSVRNYuGqutSqj75bZCZcBhDt6QJ70rGjiYP5zKMpMJntfRmat0noo,85Wgu1qi6DvoUYDrnOxqNvIaUBrDrRKY41C0NTvpkcfKf4UmlCXFsM6ykwR6ozRwjlWaV6A9qZPizZesCEiBOjUfrXbu1s99dRik6sseNTf02ipV0mv0ZV3KILQX3nDLulICbdxA5WmUBd50wEGDsCnVxxEW55jAjZpFzQXNmaAO652hLWidIFO2sr5qn98rqJLePCHzZCUA0keCcdX22rwiH5lICp5LLPD0cOOSnfITEmvgyDdep3x4bD04OPZ3,HmbZBhbY2jEHfLi46FLIwOAqPLr9HfSweHKyWTxuyFP7stFkukQSTZakgLMUNq6Jhbx6oyNM73rFflPmFB4qgvVJc89LSHXaAg8iiUSYQ9N268NG6YM6YVjAoUgmnIbZ89qfJ7nonYIfm58al0ToOTkry0apnekgLyIxBMWIKB53bGxeBbKfg85OvBRPJGX96T2VF4M4q0myT6EuJGyuG8l8eNqx68ppjefzfLV4aPDWgbL96TvajewgXSejtcrd,cR6kkmOGqqOEdckt2yUgjllIS2BMCzHEeLXBTcTnU3B9eVSEK5J9gRMUZqkv4ME1aQIAB66I4YQoeHIlSZvB6SjZXjCEIk92eb3AK0qVveIEA4kCUwDHcncktNCTFVHBQRH3CC8bd7Ti0eGxhNWq1XYLFaAUyUDrDWUDtGps2txDE0aBR4NNzfMzLzQzNVTHg4yrapLk9t4jPY5YZbTXXgrbPjcLSs1qSAFmvGP1sBRoyAb6I4VGyPlwOoUbf4cS,iG7sIZuC7QXARDQGwJTfUdgRZB3dWw7eWsIfF49DbTBiCbpX66ff44WnhJKSTd9sr0KAcqt5VXf4gGrHNHPIxtNFib2XuuT3bQi6BzICZqtHxwGfSbzNgo6aG2tWyGrgs7OYxvVzZiowq5kwbFCpPu42Ra3zwDTW7nDGMzrbCHKAJwhhN4OFlHtNSK8O3q2wnl8KmZ9X1P8dptyAFmW7IvlWaTCdY6wD2FMS015MtO60xJmcR8jBnk7ZVl1VezpS,utY9pWmsUmcZb1KARitSGLShkvv8ubzSH6IrjDrK5vhM9YZUGZGt7GirWXtOIeVRjW8rAV95tPbijOcX13QwtJ8YDZdRS7FFWRxB6lNmFu6YuS3Jp0QIlSQhBNeFqdgqdsSdosTOsbEVTDWPJUlUnfyMzZFfmtIpaHIPeaP6nyQpWcvXoQ3uhtjSQLR4w6F2R6XqPQMLN2NgLlD56pMvXlJMpJNUhg1FWvuxpNcjSC97q31EtW5qMnvrYs6wITYu,aAoN0U7xtMxODP4cJjCp4JIZyqnY0OhW5MxBcQJ23GUrTOWnJEkWPVKlTpe7o5ZImIRbOhweouMUBVE6Tg6tACFigxZENKRSJoTHESsbshve6nzEBypATO3M5uzNeDVORxc5n2UptS9hXIOVP6y6FKTCFOHplx7QPwW95LqAChh1YHonSRQ2VIw2BvpjFDPnoI7XwrMoOcCVx3YLFa9pkXneqGEvuOZCqtRCjc1UkcSA2E7oyhGKwNW8ih7qR8PI,7GNoCx6HJTnm6GSRGo1gLDfwGZ0ppYZ5dfnLkPc8CrcgFtTdnlKihbvoPipKFhuiZ3GEk2f9lTAFATsNmZ9kYSKRIJqOjwJC2xdJu3t4Rqm503euhVOGKoCqDHtsHZFuk1sl9F8u6DeFKFiMNTP7HAvhNTREXex80u5bY4G353y6Icw6MyFLWJ5re6MNnAbY1VdBhtyA4bNGYg8rC8Q594myCRDuXlHB4v2aPf15BanfIRxxGSt3EIq7HkkQet5R,P3FBT4v0oqWAgRxMANX5vNfFCns2U54Jnzu8Ui4v2EDLuV75nCxXuHUzArsM2J5cZZD8tJWZrdCiSjtgO7w8Sh0gToAiEhVCsFEgPuR2mVZ8HENhEinEo77NSTLafJSK3QM63zgPUHuZdOi3zIsSfsTeqvBggSuHK1HDQ8pIwOobVR7a6awWFPMYSSQXH0ohH8NrJu9qDFWQKraoJHXzdQ8apmiTcH7YvcKvj3xQ5FFLl18xAd9IEM9GHITn83la,RZh57cgtplJHYNtduxg4NzcCY6yB6YsR6FLQDvMJWob7z3TxoeDogasncPK3NTaOwAK00ueRQ2sJQtBC4UTAGipi1LBl7MmboHVVB1u1Y3SfNtldAa4NMeezgSsVkN1ATbX0ePLmf0rLb4Q3ybrWCDIIbUowq39QQoCfaxQGOj8wITPkxLgJoQcmdCHEp80pjsf7J0fweuYOQrL1tQE1n6Ey7PNySsesjqfk3PnTI7uyIryVYgzEexXjqhxfPrms,tAcwW4Rzwy0TbRqLkkEs80FaGQR5IpusP71mAyMaU841dz4R8wDmBZ8bqZHb4HwQCGCvbRF1s0Wc1e6aumuFWZqpzjTDhdP3YPVmm6bgyiL2cVshiq46WCf6YALV2MZ40Dktd13001GZwtoUKSACiDLRj8rJmsExIDbxOokrJpPAhCDkkG7fulcGyclA8XVbw0po2sako2MRQ5ATxwre2giszDczJ0jGiB2kqF2d9qb2Je38M1FckaOoLQKLlqQu,QZGYm7wBvZi9xBCA94H5awQhEFXxmJJNecTLmo1y371alpT95eSbUY8lqqfTCkejJekMWHGvQsAur9Oi7rnm6NdZ57s9uig1Sw6XodiULKZoqigB9yh5aCYX69Pgl1PxQANWv6jBg3mUkfVIxrDIiiZ2CzxznUt8cCBOI2vvdPKf39ZOmInq3QSIJcU2TmXWnw4Q5b39Z5TCifk9uAZqG1ntW6fOWj7Fx5QqgAZZOhaTLxWX4PzkGZJ5k6FEIyZB,7UijKBfHq2JrvjvYWa1HmkhGpb9fqapnQ4RNyVJIBzsJVXHA5XGTVaqXnmrwLwboCzPNVZlAcbhX5C7xxJmWXzYFyr4fvwTNxlC9leJ25nbpefgYYqzup8BNkUUD6JIfaPf9R4zO3cOpTxBdTAz5rLfs2sj2oUqoYcgej3yKQGiW9Kd18PdfByW1CRsrqPvOIrwGQbaJjFoKrBbfNN7cUXrHda3AYpeW2fu0q53zWM9rkppzLnf2sO1hThCDsszC,zko4ijPgxFUol7pGGD0SrfAHZBjCmOVysaAR3VnxBGrTVx1EtDjWkkKQgqUorqprICsBOzC2K2LmDkvPXOZAlse2KXl9q3q0LC7KLuSAkqZ3LzNsB8o3WTGVlQXQudVzSbVpFjOpkarpACZ9kxc0OiP6FaHD6ZVv1ZikGh1SGqisiEcZi2eEaFbH66pwr28UcxOTnlfdeextIARBMgcXez423Ow5UtXmgDVdD3mcRNsutl4hpnq1uLyJTiCYVUPy,3JinDEVibxR8jU8dBbWIVCr0OqZr7LD1Hpfs12kuRQtUSe2zRgafbQjDQZJcLxbOfRJronxaTlbLkJ7n139TtT9NtUC2M2bAXONdxmrePXf6Mr1G6dyVp9q87TEsV9IH3jIgezr6IBkYbUP5oU7RurrtWj6QnZYbtQsOyqIRZ3Vs9bznBNJq4b1cMHo27o3yXIFjwaNd38GxxvKodCaXTMSpUf1inwHNHzCdY7isrHFgfBZcj1BmQQbuyh7Od5hy,vzsEXkL2W1wkGdg26IVW8KfBjhNmiCPay89JiYhJkosBth7lFgnf1hlsKS5OZ2llSyfKDZDrUyPu8Ux7Phw5wGGbzM9LUXQAdKn2T8AwGPfkLILsLv7Ax7VAh7xplYXap64eI4nFro7FzEKREOxDqWtqO8hNHo7H96xpc8R0BPKn5QPuzBXHTh9G0Nrk4vOhMEMuAU7IUKpjA1P1oi2PULgOnkoPPaO231mDK67JpTnoQprRbYfTV327QhWeTfby,5ZHJo2gexKgAFF6f1wDJfcjWlt3nlQDNCK15ujAe33qqSaX5ZHMSOhHmSQVXhQvpVpSowS4agCZ64ewlVkStk3Tltrq6JmAZdbhUlW8N1toT63My38hRG9g3SLDTecv0C2GyEE4RtwsZYBiUO7YBOVv14eKzKzRz367yWy7wh4zLTSSM8Ach9660q8hSB4MNZzzh8oogQs4dTu54hUoQrLwyj2UvCNCtQ2t8xbUzBgblGO6d902OeC3wCMIPbMfA,WkPUinVfgsAE45rlhI3f9xdTnXtYKjvKQeFp8MhZpUdhIfG07bvhjHu04FGqa2SvVCv2C2GUaLjD0Aldzr6fU7lvhE0kQchSmiEUJyDIElqjob4NUorkCNAhsA1TGm1Cuxg5p0x8R6ryrNkmXF1SW6Odab5eCMUB8Skq89qHqgDRBduoPXcxUjWVlmQbLOzQ04T1SXaRuLoktylnKAmFGwYsRa0GHIYf6XhmPLI1mgcAfUbWU9vsMfmMoGcRsOMu,obdLT5rXVp5E5VV0GCkjn659Lu7DZ7l8OOv4fthiMmqzxtCazHCZQjy6rifGogDAUVpQzaXPgCE25dR0G6KMfCzsEDc7SIZyqlNRZXhTigfhhsruqmZJKQBt0Ztrw68lcWj7HILaX7ljxEV5jqwkRd7EqmMu6PZpEiRY5hpJEN5twqCTDbofpjVvdU8Jztz191KCUE97S66zmjPgLqBTjXntm7IlnxbLfxITKDy6jq6UOKwU8PXQ1x1684aXJacI,uPkkbTYj2DK5lgb2e2FEkJSSyWGHPG2L1bEOZSmHvQvbnx0EKYyhmlxI2X5RM7bdCKudX3l4UaOYKtdW2PMowocD8Pm2lLRbHtIgK65erppkONRLHa4fJgzfWAYs62H0S9WA2LVGDNdW6lC0ckxIWam0nwI79lHuO6voktE7RjWE4qQabKshDU1KSSmbVHRXc5c72dh7HFKE9mQ4EfHkZYI9NU92jOOajPdLX64Q0QfKYUze3kVhndSEHTb0Fy[T,haliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
CbRsx0jHtxWydVeY4GHJEr8YC7ferADVHdRpkukyjCaMj6abghG61F3OVLarOBQ0kIIBoK0aNOQlXSB1oRYGNy3zHonJm27AZQtg9m8yt8CwRnJu0j7H3CUm6EpeWq6S1kg91neAjODhAr3T46wbW6MvqPgJZHq89q85PsgpkYepB,1hwB1cbkHOBbqP8aK4DRZddYT55PBe5r4eKICsohX6GjkmsPtxkawCf1CJGwCXVumadaE1DkyYydDyKDPv5WCRM5PQ5iWbiTk3GQbeMPzxZvHhVmwUf1BUJINx72CD4LCnkcaIDbB92bEAZZFWF0G4gKc05oB1bMhvhuGLcaVgM2M58jfWw8ZSqQfXrxVUIzBdvar3t4q1bYUZOnQhwVQ79IaBNj7MDl1f0TnrmajcTOfZjyp7rG62OdQCBP1gNz,zvJSvdOOaUQKA7CAHGVlRBp6ICYsMzstjXuByDHsjZPiIbYI4ZQKh6DSYR4RnrpMogpCXinyohc10t4TnaAGGDh3vOGeiyPrP9TH7ODxsl756W5mKbc89BpyXqV9F8olUsCvVI1bktmkQfzqHHr1N5XFOYgcojRCvWgApwkpXyOKvDEYlKVtE4Nc9i8LxtNVnumTerQcGyE2nOBC2s9BvqrR4soysBdqmMpRj4cR1YcvniMau51Bpve4tSSQQzVq,HsovVzbxRLOEpWwYsyFyjcygYiC9IIr98lcwCc2CZCZkLOKhrIBfNJkxydfDJ99XLzv93xWc1XvezTHSoWKZ0C4Wl2D3y9NMDC3f7Hp3vBWxhB5HIYOjGMqBPB6FGZJayyNmHo3BBkllMLU4wqRAjxSYIw1ZzBHhuIx5KkbrHN8msGbetZFJQQ3Hu7PCCjW35YI32AKcCwuGOECR4MP8Q3CTF4smyR5OtCdQiZmB0ZG9klUUndafFUifpMUxk[Th,aliCore] VirtualSocket exited RunLoop vsID:7
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'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:7 [4, 6, 8]
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] TCPCl,ient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] VirtualSocket.deinit vsID:6 [4, 8]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler, disconnecting:false
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler ,disconnecting:false
2017-07-13 08:33:19 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disco,nnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49816
2017-07-13 08:33:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nfK2NI0Wcajv4QI1IBcYqBprcmnIqQZq",,"error":null,"portNumber":49816}'
2017-07-13 08:33:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nfK2NI0Wcajv4QI1IBcYqBprcmnIqQZq', error: 'null', listeningPort: '49816''
Connecting to the localhost:49816
Connecting to th,e localhost:49816
Connecting to the localhost:49816
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[Tha,liCore] TCPListener.socket(_:didAcceptNewSocket:)
Connected to the localhost:49816
Connected to the localhost:49816
,Connected to the localhost:49816
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] Session.startOutputStream(with:), peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] Session.startOutputStream(with:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [4, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [4, 9, 10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [4, 9, 10, 11]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-13 08:33:20 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 112 got the same data back
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
ok 113 got the same data back
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [4, 10, 11]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [4, 11]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:11
ok 114 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [4]
,# teardown
,2017-07-13 08:33:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:33:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:CBE4BA45-6080-444B-B5A9-545B9189CA71
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49816
[ThaliCore] Session.disconnect() peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:37DA447B-8BCA-4888-A068-1F267027E7E5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:37DA447B-8BCA-4888-A068-1F267027E7E5
,[ThaliCore] Session.session(_:peer:didChange:) peer:78F6A44B-E96D-4449-B257-3BC989A80123 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A385ACA9-6BE4-4961-9C6A-7F8665F19C7C", generation: 0)
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:37DA447B-8BCA-4888-A068-1F267027E7E5
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4804A3A0-BF11-4E49-9818-17B476E274EF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4804A3A0-BF11-4E49-9818-17B476E274EF
,2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 08:33:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:50E0C008-7180-4191-B35F-D0DF74B4F541
[ThaliCore] Browser.startList,ening
2017-07-13 08:33:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-13 08:33:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":tr,ue}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0)
2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","generation":0}'
[T,haliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
,2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 61756926-9537-4B4F-AF8E-72C7D7AF849C (syncValue: IDMUnlfVJiYs4TYrQPnhU6SiMNmsu0ud)'
,2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0) new relay
[ThaliCore] Browser.invite,ToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"08B6D133-C3D4-4338-B019-A18C4389675A","generation":0}'
2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":t,rue,"peerIdentifier":"CBE4BA45-6080-444B-B5A9-545B9189CA71","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8344525-57A7-4C58-8528-26E881A5D49E","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4E6B4EA-B9F7-47DE-AB46-1F466A373B26:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4E6B4EA-B9F7-47DE-AB46-1F466A373B26", generation: 0)
,2017-07-13 08:33:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B4E6B4EA-B9F7-47DE-AB46-1F466A373B26","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0)
[ThaliCore] Session.disconnect() peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CBE4BA45-6080-444B-B5A9-545B9189CA71:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CBE4BA45-6080-444B-B5A9-545B9189CA71", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4804A3A0-BF11-4E49-9818-17B476E274EF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4804A3A0-BF11-4E49-9818-17B476E274EF", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:08B6D133-C3D4-4338-B019-A18C4389675A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "08B6D133-C3D4-4338-B019-A18C4389675A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:61756926-9537-4B4F-AF8E-72C7D7AF849C:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "61756926-9537-4B4F-AF8E-72C7D7AF849C", genera,tion: 0)
2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IDMUnlfVJiYs4TYrQPnhU6SiMNmsu0ud","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:27 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'IDMUnlfVJiYs4TYrQPnhU6SiMNmsu0ud', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,tifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13, 08:33:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"61756926-9537-4B4F-AF8E-72C7D7AF849C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:27 - DEBUG thaliMobileNativeWrap,per: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:33:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C8344525-57A7-4C58-8528-26E881A5D49E (syncValue: B7wuMl8,cL3KMk1n2zwXpyqBhubfIlGhM)'
2017-07-13 08:33:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49828
2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"B7wuMl8cL3KMk1n2zwXpyqBhubfIlGhM",,"error":null,"portNumber":49828}'
2017-07-13 08:33:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'B7wuMl8cL3KMk1n2zwXpyqBhubfIlGhM', error: 'null', listeningPort: '49828''
,Connecting to the localhost:49828
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [4, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:49828
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-13 08:33:31 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:12 [4]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 119 got the same data back
,# teardown
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
,2017-07-13 08:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:C8344525-57A7-4C58-8528-26E881A5D49E
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49828
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,# setup
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B7476D46-4931-40D9-9792-45128C802C97
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-13 08:33:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C8344525-57A7-4C58-8528-26E881A5D49E","generation":0}'
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C8344525-57A7-4C58-8528-26E881A5D49E (syncValue: nXOga6cVXbLIfHzweCrm9jCxGOjShdQq)'
,2017-07-13 08:33:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
2017-07-13 08:33:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E9FDB0B-BCBB-402F-846A-DB533AA0231C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E9FDB0B-BCBB-402F-846A-DB533AA0231C", generation: 0)
,2017-07-13 08:33:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADF8C929-C7FF-40EC-A17B-BF06E75C0D00:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0)
[ThaliCore] Session.disconnect() peer:C8344525-57A,7-4C58-8528-26E881A5D49E:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C8344525-57A7-4C58-8528-26E881A5D49E:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:C8344525-57A7-4C58-8528-26E881A5D49E:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "C8344525-57A7-4C58-8528-26E881A5D49E", genera,tion: 0)
2017-07-13 08:33:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nXOga6cVXbLIfHzweCrm9jCxGOjShdQq","error":"Connection could not be established","portNumber":null}'
2017-07-13 08:33:39 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'nXOga6cVXbLIfHzweCrm9jCxGOjShdQq', error: 'Connection could not be established', listeningPort: '%s''
2017-07-13 08:33:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"C8344525-57A7-4C58-8528-26E881A5D49E","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:39 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 ,08:33:39 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"C8344525-57A7-4C58-8528-26E881A5D49E","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-13 08:33:39 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:39 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-13 08:33:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4F2F1D66-84E2-471B-A46C-8EF9A1C2271F (syncValue: yeGEFXv,lpvU8IYCPeW9xU9bUgmFOhtBw)'
2017-07-13 08:33:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271,F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7
[ThaliCore] Advertiser: session connected Peer(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:49837
2017-07-13 08:33:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yeGEFXvlpvU8IYCPeW9xU9bUgmFOhtBw",,"error":null,"portNumber":49837}'
2017-07-13 08:33:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yeGEFXvlpvU8IYCPeW9xU9bUgmFOhtBw', error: 'null', listeningPort: '49837''
,Connecting to the localhost:49837
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
Connected to the localh,ost:49837
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [4, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-13 08:33:42 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 124 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:13
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [4]
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7
,[ThaliCore] Session.session(_:peer:didChange:) peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7
[ThaliCore] Session.startOutputStream(with:) peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,4 [4, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (20551 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (21504 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received (3842 bytes):'
,2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-13 08:33:43 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-13 08:33:44 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:14
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] VirtualSocket.deinit vsID:14 [4]
,2017-07-13 08:33:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-13 08:33:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-13 08:33:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:49837
[ThaliCore] Session.disconnect() peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Pe,er(uuid: "ADF8C929-C7FF-40EC-A17B-BF06E75C0D00", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:C2D4D6D4-0AA9-47F2-8E46-DC123E8E96F7
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
,[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
,# setup
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DA0C04EE-1E8A-4481-BC8E-B4200FDC5E4C
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:33:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "691646B5-B1DE-43A2-BC53-4028E7B0F72C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:691646B5-B1DE-43A2-BC53-4028E7B0F72C
,2017-07-13 08:33:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-13 08:33:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-13 08:33:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
2017-07-13 08:33:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}]'
2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}'
2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8E9FDB0B-BCBB-402F-846A-DB533AA0231C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8E9FDB0B-BCBB-402F-846A-DB533AA0231C", generation: 0)
2017-07-13 08:33:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}]'
2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}'
2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE67C612-B683-44B5-99A0-83F49848650A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE67C612-B683-44B5-99A0-83F49848650A", generation: 0)
2017-07-13 08:33:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FE67C612-B683-44B5-99A0-83F49848650A","generation":0}]'
2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"FE67C612-B683-44B5-99A0-83F49848650A","generation":0}'
2017-07-13 08:33:46 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:691646B5-B1DE-43A2-BC53-4028E7B0F72C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "691646B5-B1DE-43A2-BC53-4028E7B0F72C", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8E9FDB0B-BCBB-402F-846A-DB533AA0231C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8E9FDB0B-BCBB-402F-846A-DB533AA0231C", generation: 0)
2017-07-13 08:33:49 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}]'
2017-07-13 08:33:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8E9FDB0B-BCBB-402F-846A-DB533AA0231C","generation":0}'
2017-07-13 08:33:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-13 ,08:33:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-13 08:33:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising(),
[ThaliCore] Advertiser.stopAdvertising()
2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:50 - INFO thaliMobile: 'Filtered out discoveryA,d,vertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-13 08:33:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 131 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 132 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5CB8DBA9-C284-4CAB-9AF5-002C28F7764E
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DFDBB05D-E6DE-4D4B-94A6-5EF548AB71D4", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:DFDBB05D-E6DE-4D4B-94A6-5EF548AB71D4
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
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 143 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-13 08:33:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-13 08:33:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-13 08:33:52 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-13 08:33:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 150 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-13 08:33:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-13 08:33:55 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-13 08:33:55 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-13 08:33:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:b8bca726-a345-4da7-bb00-47e88fbd6656 error: startListeningNotActive
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"P5GxgT5GAqO6s5zzOp4LN0pe5us4tMVE","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 157 Should only get called after multiConnect returned
,ok 158 SyncValue matches
,ok 159 Got right error
,ok 160 listeningPort is null
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"b8bca726-a345-4da7-bb00-47e88fbd6656","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"b8bca726-a345-4da7-bb00-47e88fbd6656","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 161 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:33:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 162 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9CE3FA42-5E0A-4836-B09A-EC0EE090425D
,[ThaliCore] Browser.startListening
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 163 No error on starting
,ok 164 Got null as expected
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TUMIJftZ8rYVkM4j5BcHRmfhnMmuTPUg","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
,ok 168 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 169 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 170 Should be able to call stopAdvertisingAndListening in teardown
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3DD28BB2-6F8D-4EB3-AD8F-B63A7AC50B63
[ThaliCore] Browser.startListening
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-13 08:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 No error on starting
,ok 172 Got null as expected
2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RV5f10vJkPC6iJgpXqpd3q7SS75qGmAt","error":"Peer is unavailable","portNumber":null}'
,ok 173 Should only get called after multiConnect returned
,ok 174 SyncValue matches
,not ok 175 Got right error
  ---
    operator: equal
,    expected: 'Connection could not be established'
,    actual:   'Peer is unavailable'
  ...
ok 176 listeningPort is null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
2017-07-13 08:33:56 - DEBUG t,haliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0b4277ce-bb43-4ed5-8754-cafd16e8fd8b","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out, nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0b4277ce-bb43-4ed5-8754-cafd16e8fd8b","peerAvailable":true,"port,Number":null,"recreated":true}'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-13 08:33:56 - ERROR CoordinatedClient: 'test failed, name: 'multiConnect properly fails on legal but non-existent peerID''
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
,2017-07-13 08:33:56 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - multiConnect properly fails on legal but non-existent peerID, error: 'Error: test failed, name: 'multiConnect properly fails on legal but non-existent peerID'', stack: 'Coordina,tedClient.prototype._processEvent/</</endHandler/<@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:463:22
tryCatcher@/private/var/containers/Bundle/Application/86EE39AC-FD36,-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jx,core/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:56,7:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settlePromi,ses@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
,2017-07-13 08:33:56 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,# teardown
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}]'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}'
,2017-07-13 08:33:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:33:56 - DEBUG CoordinatedClient: 'all tests completed'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE67C612-B683-44B5-99A0-83F49848650A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE67C612-B683-44B5-99A0-83F49848650A", generation: 0)
2017-07-13 08:33:57 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FE67C612-B683-44B5-99A0-83F49848650A","generation":0}]'
2017-07-13 08:33:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"FE67C612-B683-44B5-99A0-83F49848650A","generation":0}'
2017-07-13 08:33:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4F2F1D66-84E2-471B-A46C-8EF9A1C2271F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4F2F1D66-84E2-471B-A46C-8EF9A1C2271F", generation: 0)
2017-07-13 08:34:07 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}]'
2017-07-13 08:34:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"4F2F1D66-84E2-471B-A46C-8EF9A1C2271F","generation":0}'
2017-07-13 08:34:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FE67C612-B683-44B5-99A0-83F49848650A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FE67C612-B683-44B5-99A0-83F49848650A", generation: 0)
2017-07-13 08:34:12 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"FE67C612-B683-44B5-99A0-83F49848650A","generation":0}]'
2017-07-13 08:34:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"FE67C612-B683-44B5-99A0-83F49848650A","generation":0}'
2017-07-13 08:34:12 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-13 08:36:41 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-13 08:36:41 - DEBUG CoordinatedClient: 'test client failed'
,2017-07-13 08:36:41 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: run failed, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: ',[{"uuid":"d07274b3-2294-4f2e-9b38-e14869561fb8"},{"uuid":"2e4e2245-ee90-4904-94d9-3bf7348c53ea"},{"uuid":"d3c978f2-16c2-4405-ac70-2305e0d7fe9b"}]', received data: '{"success":false}'', stack: 'CoordinatedClient.prototype._customError@/private/var/container,s/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules,/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/,containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/ww,w/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/86EE39AC-FD36-4865-A8D9-C43DC965750D/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-13 08:36:41 - DEBU,G CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
