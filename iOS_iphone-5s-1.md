#### Test 1133518513e6abb0_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1133518513e6abb0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/9301D251-BCDC-4A4E-9304-C98D6C852C2C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9301D251-BCDC-4A4E-9304-C98D6C852C2C/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1133518513e6abb0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1133518513e6abb0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59058"
,(lldb)     command script import "/tmp/9301D251-BCDC-4A4E-9304-C98D6C852C2C/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success,
(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-21 08:40:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:40:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:40:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:40:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:40:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:40:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:40:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0C18E1C8-2F43-459A-9B,1B-E5D00B870890", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0C18E1C8-2F43-459A-9B1B-E5D00B870890
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:90A601A5-3A62-4F4B-B8FF-ECC893EA993D
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_liste,ningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:69E02F76-EE46-4F7C-AFA5-96D01E8BD1E8
[ThaliCore] Browser.startListening
[ThaliCore], AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "17315B2E-0B1A-4843-AA8D-053D5447A48C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:17315B2E-0B1A-4843-AA8D-053D5447A48C
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:17315B2E-0B1A-4843-AA8D-053D5447A48C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "17315B2E-0B1A-4843-AA8D-053D5447A48C", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-21 08:40:58 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.415363073348999
,2017-07-21 08:40:58 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-21 08:40:58 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:17315B2E-0B1A-4843-AA8D-053D5447A48C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "17315B2E-0B1A-4843-AA8D-053D5447A48C", generation: 0)
,2017-07-21 08:41:01 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-21 08:41:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-21 08:41:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-21 08:41:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-21 08:41:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-21 08:41:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-21 08:41:05 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-21 08:41:05 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-21 08:41:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:41:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:41:58 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-21 08:41:58 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-21 08:42:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-21 08:42:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-21 08:42:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-21 08:42:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-21 08:42:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-21 08:42:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-21 08:42:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
2017-07-21 08:42:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are, out of the checkpoints plugin delay interval''
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
,ok 25 thirdPromise - in resolve
,ok 26 secondPromise - second to run
,ok 27 secondPromise - in catch
,ok 28 firstPromise - third to run
,ok 29 firstPromise - in then
,ok 30 testing promises
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
,2017-07-21 08:42:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-21 08:42:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-21 08:42:33 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-21 08:42:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-21 08:42:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6918C725-0355-464D-9770-94B96549B8B5
[ThaliCore] Browser.startListening
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":false}'
2017-07-21 08:42:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments",:{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserMa,nager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9AE5794F-99E5-4587-9F18-5BB9190CA4EA
[ThaliCore] Browser.startListening
2017-07-21 08:42:50 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:42:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 08:42:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-2,1 08:42:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,,"networkType":null}})'
2017-07-21 08:42:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9DFCF078-C86B-4E10-AF8F-FF7E15444B70", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9DFCF078-C86B-4E10-AF8F-FF7E15444B70
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:51, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-21 08:42:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Adve,rtiser.stopAdvertising() peerID:9DFCF078-C86B-4E10-AF8F-FF7E15444B70
2017-07-21 08:42:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:51 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CE81FFE2-7F1B-4B95-BA57-FFDD9F908E06", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CE81FFE2-7F1B-4B95-BA57-FFDD9F908E06
2017-07-21 0,8:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CE81FFE2-7F1B-4B95-BA57-FFDD9F908E06", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:CE81FFE2-7F1B-4B95-BA57-FFDD9F908E06
,2017-07-21 08:42:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:42:56 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:CE81FFE2-7F1B-4B95-BA57-FFDD9F908E06
[ThaliCore] Advertiser.stopAdvertising() peerID:CE81FFE2-7F1B-4B95-BA57-FFDD9F908E06,
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped stat,e,).'
2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:42:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:42:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:57 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:42:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:42:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:43:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:43:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:00 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:43:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:43:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 08:43:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:43:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:43:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:43:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:43:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:77BBFECF-121D-4B80-B600-51C99929A3D9
,2017-07-21 08:43:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:72F85878-FB48-4602-BFD7-0D8CE08A573D
,[ThaliCore] Browser.startListening
,2017-07-21 08:43:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:43:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:43:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:77BBFECF-121D-4B80-B600-51C99929A3D9:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "77BBFECF-121D-4B80-B600-51C99929A3D9", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:77BBFECF-121D-4B80-B600-51C99929A3D9
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EA866320-E8DD-46F0-82DE-6644335CB228
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:10735B8E-6FDD-43B2-931E-5F27971B2749
,[ThaliCore] Browser.startListening
,2017-07-21 08:43:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:43:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
2017-07-21 08:43:07 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"06B916F2-4AD1-4258-B3BA-A806E40E233A","generation":0}'
,2017-07-21 08:43:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 06B916F2-4AD1-4258-B3BA-A806E40E233A (syncValue: EHJ141unERhQsvkKSRb3maNYfsYviw4j)'
,2017-07-21 08:43:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EA866320-E8DD-46F0-82DE-6644335CB228:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","generation":0}'
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
2017-07-21 08:43:08 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1211860E-3540-4274-8371-7D60BFB282B3","generation":0}'
2017-07-21 08:43:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:08 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:06,B916F2-4AD1-4258-B3BA-A806E40E233A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,6B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "06B916F2-4AD1-4258-B3BA-A806E40E233A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EHJ141unERhQsvkKSRb3maNYfsYviw4j","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:43:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EHJ141unERhQsvkKSRb3maNYfsYviw4j', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"06B916F2-4AD1-4258-B3BA-A806E40E233A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"06B916F2-4AD1-4258-B3BA-A806E40E233A","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:43:10 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:10 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:43:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9AB7820A-F8F3-453E-834B-995FF5171EC1 (syncValue: xtOrMwdoXEYeawpDgfANhxJc9JQQI8gn)'
2017-07-21 08:43:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:43:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A15BD485-472B-43F5-B1FC-EFC96900E0EC
[ThaliCore] Advertiser: session connected Peer(uuid: "EA866320-,E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A15BD485-472B-43F5-B1FC-EFC96900E0EC state: notConnected -> connecting
[ThaliCore] TCPClient.init(didReadData:did,Disconnect:)
,[ThaliCore] Session.deinit peer:06B916F2-4AD1-4258-B3BA-A806E40E233A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:71FCBA03-E2EB-406D-AE4F-08E2013592BB
[ThaliCore] Advertiser: session connected Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:71FCBA03-E2EB-406D-AE4F-08E2013592BB state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57384
,2017-07-21 08:43:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xtOrMwdoXEYeawpDgfANhxJc9JQQI8gn","error":null,"portNumber":57384}'
2017-07-21 08:43:13 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xtOrMwdoXEYeawpDgfANhxJc9JQQI8gn', error: 'null', listeningPort: '57384''
,2017-07-21 08:43:13 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A15BD485-472B-43F5-B1FC-EFC96900E0EC
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:A15BD485-472B-43F5-B1FC-EFC96900E0EC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:71FCBA03-E2EB-406D-AE4F-08E2013592BB
,[ThaliCore] Session.session(_:peer:didChange:) peer:71FCBA03-E2EB-406D-AE4F-08E2013592BB state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:71FCBA03-E2EB-406D-AE4F-08E2013592BB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:71FCBA03-E2EB-406D-AE4F-08E2013592BB
[ThaliCore] Advert,iserRelay.deinit
,2017-07-21 08:43:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,08:43:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:EA866320-E8DD-46F0-82DE-6,644335CB228
2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A15BD485-472B-43F5-B1FC-EFC96900E0EC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "EA866320-E8DD-46F0-82DE-6644335CB228", generation: 0)
,[ThaliCore] BrowserManager.disconnect peer:9AB7820A-F8F3-453E-834B-995FF5171EC1
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57384
,[ThaliCore] Session.disconnect() peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,[ThaliCore] Session.deinit peer:71FCBA03-E2EB-406D-AE4F-08E2013592BB
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xtOrMwdoXEYeawpDgfANhxJc9JQQI8gn","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserRelay.deinit
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4
2017-07-21 0,8:43:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:43:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7750D55E-0C7A-4D3C-8106-EB9B35091729
[ThaliCore] Browser.startListe,ning
2017-07-21 08:43:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:43:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:43:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
2017-07-21 08:43:16 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1211860E-3540-4274-8371-7D60BFB282B3","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
2017-07,-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1211860E-3540-4274-8371-7D60BFB282B3 (syncValue: gsQ0cW12mhOWN4LR17A6KFjmF2WMwDry)'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC,1", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
2017-07-2,1 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "12,11860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore,] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","generation":0}'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","generation":0}'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
2017-07-21 08:43:17 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EDC94BDF-633A-4D81-89CA-4D03B57A38FB","generation":0}'
2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:17 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,11860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,211860E-3540-4274-8371-7D60BFB282B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE
[ThaliCore] Advertiser: session connected Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,11860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,211860E-3540-4274-8371-7D60BFB282B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,11860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,211860E-3540-4274-8371-7D60BFB282B3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:1211860E-3540-4274-8371-7D60BFB282B3:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1211860E-3540-4274-8371-7D60BFB282B3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:12,11860E-3540-4274-8371-7D60BFB282B3:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "1211860E-3540-4274-8371-7D60BFB282B3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:1211860E,-3540-4274-8371-7D60BFB282B3 error: max retries exceeded
2017-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gsQ0cW12mhOWN4LR17A6KFjmF2WMwDry","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gsQ0cW12mhOWN4LR17A6KFjmF2WMwDry', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"1211860E-3540-4274-8371-7D60BFB282B3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"1211860E-3540-4274-8371-7D60BFB282B3","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-21 08:43:27 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:27 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9AB7820A-F8F3-453E-834B-995FF5171EC1 (syncValue: yKfNsIKAVnMwK7gMw0Tawii4ljBDbZV1)'
2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A,B7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:43:27 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:1211860E-3540-4274-8371-7D60BFB282B3:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE state: connecting -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] Advertis,erRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE
[ThaliCore] Adver,tiserRelay.deinit
[ThaliCore] Session.deinit peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE
,[ThaliCore] Session.session(_:peer:didChange:) peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:9A,B7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9AB7820A-F8F3-453E-834B-995FF5171EC1", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yKfNsIKAVnMwK7gMw0Tawii4ljBDbZV1","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yKfNsIKAVnMwK7gMw0Tawii4ljBDbZV1', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9AB7820A-F8F3-453E-834B-995FF5171EC1","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B98D732E-24B1-45E1-B5D1-9838E2970C6A (syncValue: Gi2p4Tw90jz88sFLBjzuGr74fOz5B5Ns)'
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:9AB7820A-F8F3-453E-834B-995FF5171EC1:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:30 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57390
2017-07-21 08:43:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Gi2p4Tw90jz88sFLBjzuGr74fOz5B5Ns",,"error":null,"portNumber":57390}'
2017-07-21 08:43:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Gi2p4Tw90jz88sFLBjzuGr74fOz5B5Ns', error: 'null', listeningPort: '57390''
,Connecting to the localhost:57390
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
Connected to the localh,ost:57390
2017-07-21 08:43:33 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-21 08:43:33 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE
[ThaliCore] Advertiser: session connected Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE state: connecting -> connected
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:96585F97-EA63-4067-89E3-DC97643C6672
[ThaliCore] Advertiser: session connected Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:96585F97-EA63-4067-89E3-DC97643C6672 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE
[ThaliCore] Session.startOutputStream(with:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:43:37 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 08:43:37 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 08:43:37 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-21 08:43:37 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:96585F97-EA63-4067-89E3-DC97643C6672
,[ThaliCore] Session.session(_:peer:didChange:) peer:96585F97-EA63-4067-89E3-DC97643C6672 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:96585F97-EA63-4067-89E3-DC97643C6672
[ThaliCore] Session.startOutputStream(with:) peer:96585F97-EA63-4067-89E3-DC97643C6672
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:43:40 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-21 08:43:40 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-21 08:43:40 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-21 08:43:40 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:3,
[ThaliCore] VirtualSocket.deinit vsID:3 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
,2017-07-21 08:43:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:9F4AE99C-CB76-483A-8EBC-33C6B96E91C4
,[ThaliCore] Session.session(_:peer:didChange:) peer:96585F97-EA63-4067-89E3-DC97643C6672 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:96585F97-EA63-4067-89E3-DC97643C6672
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57390
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DB48903A-15D4-4E13-AAB6-29D52EF90BAE state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "9F4AE99C-CB76-483A-8EBC-33C6B96E91C4", generation: 0)
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Gi2p4Tw90jz88sFLBjzuGr74fOz5B5Ns","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] BrowserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:43:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2F0D64EA-6A39-4832-BCF4-85D6FEEE6599
,[ThaliCore] Browser.startListening
,2017-07-21 08:43:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-21 08:43:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:96585F97-EA63-4067-89E3-DC97643C6672
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
2017-07-21 08:43:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EDC94BDF-633A-4D81-89CA-4D03B57A38FB","generation":0}'
2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EDC94BDF-633A-4D81-89CA-4D03B57A38FB, (syncValue: rOyX5Qm7tkMEzi0W2kPqYF3oVvmMpuZF)'
,2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[T,haliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B98D732E-24B1-45E1-B5D1-9838E2970C6,A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","generation":0}'
,2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B73B52DC-F7A7-4412-9E88-BAB14F24676C","generation":0}'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14", generation: 0)
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14","generation":0}'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,C94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,DC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,C94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,DC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:ED,C94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,DC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EDC94BDF-633A-4D81-89CA-4D03B57A38FB", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"rOyX5Qm7tkMEzi0W2kPqYF3oVvmMpuZF","error":"Peer is unavailable","portNumber":null}'
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'rOyX5Qm7tkMEzi0W2kPqYF3oVvmMpuZF', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EDC94BDF-633A-4D81-89CA-4D03B57A38FB","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EDC94BDF-633A-4D81-89CA-4D03B57A38FB","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:50 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B98D732E-24B1-45E1-B5D1-9838E2970C6A (syncValue: n6mEKLnnGnPVCpSeP0LZAUdS07O7IaQJ)'
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EDC94BDF-633A-4D81-89CA-4D03B57A38FB:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:43:50 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,8D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,8D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B9,8D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B98D732E-24B1-45E1-B5D1-9838E2970C6A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:43:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"n6mEKLnnGnPVCpSeP0LZAUdS07O7IaQJ","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:43:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'n6mEKLnnGnPVCpSeP0LZAUdS07O7IaQJ', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:43:58 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:43:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:43:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B98D732E-24B1-45E1-B5D1-9838E2970C6A","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-21 08:43:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:43:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:43:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B73B52DC-F7A7-4412-9E88-BAB14F24676C (syncValue: nmGD8dRuAOlFDYCgpcC5WY4,SS210G60c)'
2017-07-21 08:43:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B73B52DC-F7A7-4412-9E88-BAB14,F24676C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:43:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B98D732E-24B1-45E1-B5D1-9838E2970C6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57412
2017-07-21 08:44:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"nmGD8dRuAOlFDYCgpcC5WY4SS210G60c",,"error":null,"portNumber":57412}'
2017-07-21 08:44:01 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'nmGD8dRuAOlFDYCgpcC5WY4SS210G60c', error: 'null', listeningPort: '57412''
,Connecting to the localhost:57412
,Connecting to the localhost:57412
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
Connecting to the localhost:57412
[ThaliCore] TCPListener,.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.c,reateVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
Connected to the localhost:57412
Connected to the localhost:57412
Connected to the localhost:57412
,ok 91 correct string length
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Client data flushed'
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-21 08:44:01 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
ok 95 got the same data back
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams,() vsID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
ok 96 got the same data back
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 []
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
[ThaliCore] Advertiser: session connected Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
,[ThaliCore] Session.session(_:peer:didChange:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
[ThaliCore] Session.startOutputStream(with:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7, [7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
,[ThaliCore] Session.startOutputStream(with:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [7, 8]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
,[ThaliCore] Session.startOutputStream(with:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [7, 8, 9]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-21 08:44:06 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received (7878 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server data flushed',
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received (5434 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
,[ThaliCore] VirtualSocket.deinit vsID:7 [8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocket,DisconnectHandler disconnecting:false
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server received all data: DCwdf4XywIgqcuDyVxYYqAog7GoN0cADyxkLJQB41nx9EezQFD6oJnnoiPu7OWyqiNcIKWt9YGNN0v6XcVnCnPA2RYdLkNj5SYCXtbuEWwiqv2RGnPzJCl3poZLJib6oaDoc2skOD15ntiQIPfrhscUGmMBc6oPd4d3qWd0gNtpeDvELZs,gTthA9KSRVdVdjUTagKVlmsTRAvXdGgET0BHdJp1wX2F0EzHcQOvMaJwX5rJlALrtxupXuTMH364zjgt03ioUmxAw1LF8XukNW8iCtYEQrJQ4b5hVJw05frVjhqAHFcf1Jm10SN4QphndHsjBOftHBaAK8NxLGsUfhDslAGH5CwPirkWVanJZFKTPuZHpVLB9lgGUbqWswrhbmpQasXVNRgctoM7BTcE7kr6SiW7JSLeQw5aBFvKYdKh1F1TYzKT,wwQCoZYJiaffkrfpRuodINeciIwPrgxFiPo3uTWzkfiaXxTLjUT5tddDtbdGlaTboIeUMcidAq1NRgStmDLO7qlCxncH1CdmjDkvMR0P4m8bNCnRIoVmnD4NeG3dhiQwpJZ86lTzNAStBnpgCGSQzXQ39TsQXjEcGKKGx1ABAfzdArJDWO8jn29kSpXD0KLnbpSNLLAJ5Nr0ivdrUGO9ekCaiHiAd8Gbf1V1QifVg7gp742A2MrrZHwxWf0U3I5o,70OdvWDWzJhGQxnj9eyaPFl8DEw2QwypFXZI7hzvAmrbHDqfRxQKSIqFR9oydvLEijC6yXfj9n8TNE7sDrUuIX8iMwJvmfXnM3JDInLjtKMDtt1cenmirt5Sfg1F3EVODOYd4Ai8AhsvqoVLCoCp7mG9e7SZk0qCx8efHIIzb1vpqEowGABTeQxoi8M0AYdmffzRH25cGvOE3zVfVg7n1vsWAcLbUrdqzMEkYLTVxiuGuPR36oTP8C5BgNLFrIhl,Mana7IHQmKJojmWJ8h6VQcA2HygtO723NAAPJzKDavakRAtBxW5MJZNbyHnSh0oJRRNyHO5wAWCsoRarQPYUsbCJBxoIOgXoUCCe8IEq1NbVbnVvtyhSSfgrO1Zn75kn8HjfAUESJlOWXv0sMsyB3SnH1GUwUJnXReVz1NjnmnEEYRNO4X4Z2oF5lvTN9xkmJ8D4whkfTikvuLjDKcAwniJ8sKlQrX6dkz6sZEzkRop0hlFqMWSjPMXnyEjotYWq,pQvav0m1KvfKluVt90f7z4VbEeOJaXvkPivdTTmbf9uRrUpOBPcMheKmBHXIjQ8rnLF2fbKElZ9TRtTq2qz7Mta1cKI5XRYnU3zmvAQJqeFT8L6MY2L2nfnHEUuHtCCK4OX91oBXkrU3QCE4mX92BcVzgWtilDBYGwnf01Dxbq63Dwhm7xWXXF4AyuI7P4GLwhOxkl98tLy1oUP1so5fx0iQT4KasN6iYPQ8UfXaVfY8XYsiWZFBeGYtA20zf3Kq,n4cckclq2MgYPHoXGZUodu1IF9qzYVy42FYPbI1C9MddzUgUTL5zLnmZGjNh29XuVM510gpeiUuVE7D9fYVolK53ahoV5e0eIU4P4GbBAtDBE0CXTNTGj43GiFYQO99cHBKNXNtIi4kdMuefgI2zaSL1jV2iLVSZS1RqFYoJxNB4ck3cJShu92fO0rWE0Wlmm71eCxvegnlDe9els9JnnNpeQmfcXw4jJZThg8Cpzyek5Vj1yH06bysVSSXPtu6a,u6TviejYsBd3VQxzN7DaiHzlAeIl2YaOaPqSlFFzwsvMwZUETrGI1u2PVO090bMJkiknGaYpOmZguvneyIawOMxDGGoAFgtLW2ote6JZ5CbJy2WFwbbJwyiAFGN0oZpqx2GY0nvbU4gUk1C9RRwx3kAEmNynulYaFvCnDV7OlC61liWU360xDdIQqsxcjATHlYHFJ75zXHUXI4EaQG5TKGIfrQ1dR5va0qcbyFMHqADB16bmOc7pqOHqQ4d8bb8s,1nWXULDw8YbjZSSvtW5SELBaxLKV0hjvnKQeQiHF4LiEx2XETX1kg6oe0SCZNDbHy4IFYrLYijdd3sARCCPi2HEqg4jbuMzkPTrcFUwAEpDVZrG5LBN3wA6LQOk7JuExY7rXwOK6Yng3f4Pl4a0Ai5ZoLcVts6kpBQ5aaDk4DfRliCE6XUliy0dRcVFPZYhpqyghAUgCcVJpgBG1HxRBAtFYu7Pc4D0kFUGqPJ9Idb0bxfLRwfFGSgP8IPSbu3w7,IG3IjtsCu3VTWyHLLK2BM7j2zBjkR01gZuAsViurwWx1EOYehThvSDrTSekZvY40fDyVugdMmy1qAufxneqzb2jllMVt4lmMDLKsGjzoxhDr2Kncxl5Boqa5JuWajMmojDuYgpFEg1XSGlHD6I9hMF6XgpcG9UlI4fPxxYV2kMCSkX0VyMNS2SjLg5dXfQMM0ToW1RQqUoPDuunXoEaUSIaHekftinXpBt0SySqw4PlgWKQMYALsXDiDn17c5J0d,lA1fRUuOLuewgAFbrfCcjtt8G1S1pixAnVXNCtcT7lYFosvwIRK4rGLDPtrUJqhKs8Ud28dY81dLbaC39JmvKrnOmAVchxkipD9qONDMI24M6GqZojvY5g7ZHggECnPf39oW0oh6bMv9ZBPgh8M57903rVbbO1EcEkf2lvAJathlYNy4Knme2ZRoS9mFemezGI6aa59onLSfz9UWyrjGYXUqDQH1YDsCDGPIheEQZ0nokVrktWLoWrDNgph8EYVU,D6mELVspBudnF2DUB8q5SglIqL0UZSLhuxukX2ptmXoydbGoB8B91aaPQVxCxIyyKvLZR1nVlZHSwC1LyhiTMGVKQiOuMBqNVVocsD26rdkFkbGpBk3lLoH3UpZFrjXqkrUvJebvNlOxQME861YKFHVmNntlI3IEeHVV1muvdfAvsjx6x8sbEoCunLwvrF6HSgRPPMHmAt9JM5DzFeo3kMXO8LRXzxSSGSTmsYE6jT3NN62OFYsEFT63V8fwhiRy,xvn7pmsgA0QuwMzD8ZNqB7JTWUaSvr6JKAx1kZyng1knm8ciEfeyopjOXE9eJgJjaCh8zQybF5xcsXcNq4L7zL062HXBpe0WBOZHK82obLXbJ5aWIqck0G514Z7VmgdHS6MW299LmVmMiguW3M5Whv0M9zGVjED4FfNT1qRuKXHTCWeOyQRE5IoMCIbpmKcbIVOpghqCarnBkbCyM9sqE6cQITqIj9Ugy3JUA5jotdiuIaWkyeYHA5XQr5qla9lG,EbMsUXJ9QTtHNlyCAKd7GrlsVp0USlHFiNoGZSrMSNQk3p018K49pbwco4c7bixRsUfITp2k2ZrDLi3AO9uFr0xNBDd9vOcshZdl69tcOk5ltETUf98obLhpxBRrKQWWxIvYxYA0pqYsYuKUlJqjy8U3feagigj0D5BO3HgCVtZ298dVAD7iKAz9j72fLDik2IBt5Zhhi8gr1h98OqVjXIbEduePNQfqW0XG4iEvycjG5eTyyK5sLdchotaHzO2G,oRe3XtwXr7aGS4wByhHFrprURd8ZIIyYWQ9dgjlYfuZQs8Afo0rqPMUwuydsRJcOuuBclIIotG0ULE1VIKFYnne1LkNKDV5jP2DoCup5mOFW9M4aJqEYvraJkVtP7ZNLhnslnxALJ0UkFz86Q0AQI0hOLbAZJvdJ6JrNSgsYjiMN75FapeQjAnfLZ8efer5hoBFo0dFIrQsaSkh5d57GRO6EQNnpN0bTVcRKgt2JcTIoSuOBNNyQn6Jbun8l6xGr,6n9afmqhM4v0QJdSMW8gaINzePksehXtPnBIIopanI3TFxuvnWZ37ZxR7g6KPhCqH9mRJxxxNLeo8jLgdzPanDmJaimKJZmaCzqEAYctdGHFWZDqqhSuBn2HfhHwAupwpzWRJEVmuaMHaLMQgJlJdwnphYPeygaMXnmtwUcSwIsKe19WYa1nA6vjTFlUJ2nPAWcURvMIsfWQCkkLbNRyih5s84j5mn5WDnpeglayeNGpzie4tm1R2fRLvtQ3RXbr,UVZ1DLyJ6gHT9Vl2b9bZEUni9PnCqXdTHj6m9L4Qb0k9Gc0HgAwdLkawphywzKDgzgrJ8KRZhoFU8FOGqH3ZG2OQCsEX8wkm03EszG0mexX8J4z9iJjfYsoK7tCvZ5PP6j2366z7WiNFJkr8YC1kOfQfIhqiIw6qCY9lk6x552qyH4lVnW9FFgIyiqvaxdMXEQfgnP936eNfuYnqVrefBRAj9xWlKpuEifzedcW9ekRgLYG0JNAocIdk2mHJ4Ljq,ywWOWTaA1EARATOTt3yWUOfjC1vTMdrYS7cOPoBQiUOWez2hhha9ozMmmeCJE6cipvv0PcAP6N7ktzpVFcirgGmGUkqXM8ZmR43SLarpabma7uYPtzniSHpRMht4zlnQh6zAnVM7wwQaYsHgoGHppNfXBfA3Lrl3c80KzfAY0LKsDTi7FYEKZSLlxCRSaW7l5F35tA7TAkeXLmSEPH9PIGAakQkzBLD37ilDeh9J7tCEatFuylL2GwvE2aszp0sk,rgo21B41vr9AuJ69yf5WQnyyVUrNiHModOJ3WMLRrKGzofI6pyH7eVAPCfQl4LU4wqyG7bc0zgNhHGawVAUolzORum5O2Ym5Tr0Cs7djRCQiHfZX50op0LsDAfPMdGb4giNqtIpyyxn3JFzxfp18N3GehR9l7YUuCTDP03vBr6MxQH6IYt5u9i8NE6wkSwfhqViDEvzkKenixThPRd8VuBsYXSCPNUWA0SX0AwG6zj3jIbXvsBCXjg43kQEl1fHk,yuh9HTDpPLZBVQanLkurduGlTOFEQruxUJ8H2lrhVNm7dT2EmIV2S8YOb1M64Nk58hplHyDp3h3OH83bPcdJWWNf0l9chzMAR4yv71iceRthcx1PAsn6jG14dnVIcf4krPaUUT9nOA2UrIoeSQsF2dBllWhuMsYkN9G6VIimEGeKRiL1rI1YanoNIjuNt7bmbQst2z4nh5G8EW4pTEpn0gGNj8gBpcs8izNh9Hsy5oNa0mYwRJQNt0liEYLHlyua,4mQ62HIwpmpn0rGUx46kAioD2B9ixnOyI7WbUUanpTh9OBocGxo8CkNkJS19QL05drPmO2CPBMCjHEOdUtlrDjxdzlmwD3Mm1HBZbsKOnM0nCiOlL3dQBog9pELSXOJJm2gFJhw9a2662q48RUPEKpbfsKQmMAY6XFNmCglcYK2TUUVR5X2s3Osi2KzI3rDgTMrKYBGA8yYu3pYpjppJdVXj57BS4R70D2Dmmc1fjBR6EenYcvltYWBykcA3afmz,gUOmNmb6gOVwERnPOOPzipxDzlqOo6cUQTUkIkEcF5tBWM1pJFeJRT5OxuRX7I0oJ3cgFSPPHRt8w8xM0N1Fc1kGG9PaoARO2Ovn0Zbi1hTzRA3kd0jtEm2xjfZbQMbb7SJyXN2q9vGVC326Qu1quV5OhCoeEjki5d9hxemiFJvq3eruiGFlJDrztFU6zavGaat8mdDnry5HQZ9oDRSs1BUP083OsKo2sBDCr4pl5CaAHhjYj0EVd7oTp9fEHi4E,Trhk4cBT6CVsctwcFAxNSJIuyUSN7NIa7evRsQ1DBj5oSwBLInombq29cEdg5Dh2EHdZJGMkkbOCvuQvxIDxKpu7bINnNq04usqTJKOalffyCEvt4Hb47kV6cSVo2gXosvhWqhlgypYWTpxevKtuOZmnR0JUx95867pLSTPsyVMU4ID71wqbdHAqesXIez6gWpUadS5NbZ7Z4mMNyOKyBGlRY63h4zC2H4aGMSZj2g9edQX8tKOOGnSLPfeImf10,QbzbwBUxHsq6SiCPBokO3lngZRsYTcCmlCho1wo53Er51OkHVb0KikoqM15ulRzCMJJfz0jXLRt8fneCtWCnakmJoJt7Nh9GOwgBiIuTTvLrXTHDVg2WJgqexksUUG1KkNEI4P0cEHSQinaXWMRYqGfF4Buow1VVetixUt9yZgMAJaE2sY8jZL47jPZMcD3w7KBbEGizq20hLLmfgUynsTCcJPirD8zjnsq7hx9YLhWMgOQwxw7VLh97QWh9wBZ6,iIKWcHz4fZxpLdWFwshYSdVl66uMxvAIuFygWHK16mQ9y1igvri0VevxOvwilX4gtSS4B5ar6wy1VkDlR8nMjW1dQ1eOhzEgyIBKVnW8JAVPVPNJg4xcAzIkT6Zmu41UGW1977xu5ZXitacHfX0aCK1jtMVd4sF5v2UBvFFCndcWgtf6WGnsPzQdA8khFV67fBhmFTSeee18CNMitRCXRBHvXAisNgDR9c77yYU1SYdrBhZSpOaqmB6w5aouYb9Q,t9kCHblWDO73gkBsD2R1a2qW4MI5FmZrkOZCLGqdvfRnHeQDFE8yWMm1FXJRD99JyDanwhz2efefDi2OhbRoJS0pYp3wIGTfUIr1KrbIEpthNucGZxpGM5yuMr4ceS3XUwJUAaVZ4o1ZRnXnNinbail1JMHA8HF8z7m0T8B6Rj0l3M9Iu9ibsF1EI7twHG0Oz3rsbYxdXaOgwVHANVsDiFJUFCKoTkXHbMqT7ke7GEHFcaky2fjDBS84Ukr7PR0a,BFqBJY2dnvE4IN1N4UXKAKgR9EpchDjlKqNCT4F4esNAvzYzRsaPJ1dpLaFmJwXY4vdrVgEzJxKhPvOm2ASX6EUwZfUuwVcXveWo6J0A25yNpkRj3nzp4sAawuxfNWM1dkQvJ5XPQYGPH1Tnafui2jpPxrDrB1bDlGMOQPXc5lDrZRC4tidGamzLFeeDlxrFyK4FFLIIuZeWszuWOLlsr9H93IFVbziHVj1Pd8DnqKYZRX8SFUX2lHT4ZSImstMv,Mjc2pnlVhaHYV7IXbraAoNjuFN5z9Z6Gcn9z5W4R9VMwoLpyakIA8BzByT8bvtws4wC5VVBrRWbnoKSiDz8eDUtGviEIdmULP7HYP2ulCOfMTNtzhg14DowqoTJK4BtQRE2eFxmNvDDe2Y9gl10PfgDw14PlmIXqUc7eL30XCeejx2Ng54qfLq4uYazhez0clnPs5ZtmR4Re61ecQAOOe1ymM4b7A1JCB3D4gSX0Faf1u80LQqD1IxgWr0KIqlbk,TZaPzv0YCPOQb0MXHFtA13HsZSrNHJCtCSOplElOkuRq4QacOFTD8tVZ0zv0xRIWjSmpqLxdzSQ6yMI611Q9lbVyXm3P5snq537B2YTidrv7Gs7u6TAtvvaiUgBnkBo1E66HRt4EqvMldyPxba7fuQzYvPv3zqJwH7xsI2xgHv5BY7tgoAWNedVFl3CHT6P0rLYvfCHCFaN9XzIqsMWyimcKe74PHXRr2FW0AjyXW6Zm7d2oPhdSuGIZHHkLYGJy,hF4eAy8EmJf3FqbUbd9UtoTBa4aIFRsWeIs4Vcsx8KLdK7x6AXeNStbACJGQH7Zm56mR5SEu3SWB7ts7ROEE9y6MXa7S8fSDTmQg3mowlSSJCzNtWpXG0D0BoSHcEgXqp1Yq2uxrt7fycZhaFnZH0Mj8bkCOEBvQ1F2EDZGY0ydoA9xrJ9MlYCUgms2nEwVdi9hPyuKT4EX3WongD1mHeDVHC1MngUwhPytnHY5DK0sxkhkcViMab9QJ5LlWkXKJ,7TUOziw2WstxYM7QWiIEtrp6nnBT6xgEHrLalTZjb2Sv2J5Fv9Kyx6Zb0nL8qQiudPY9QjdXsTGgGl221OryteqCuYYqt6e99ZDhVSHojY3wTJQ3fTkOOCR0ZUdumgumdS2eVBpgtI0EbGEfUFlUgQ71FdxZu4V7kgo0cl8cfgCRzMTgKlg6eVNBC6cCWS7N6wYbhC7Wj8uEqK8vgyqPROZ90zXr2rz7gatwKSLuM5Luue3OVyEQIYvj8He18VZw,9HXthGDyuB3bMWvzw9vhbrdODrPDwaCGNY9QDK1LMCeUsahHfMeCwxENn6NESOCXNcSUHUTwr3QDx8EYRuRmrW6JJfNLrRz6Ji8feeBzD9LIvNjItLvpHZuFkNs8ahRUVhOwfqg6IB9IAJVVkY9EohS1RqSCZtxUq31PKUFqZBWt8FRFswfEn25mrzh7oqFVgUAinge4ETki3bJigHUjdQa46mjWGfQGWLnlkC7ruQ4V97gbaVmyb8OPxoEg32JX,AsojLe4tQOg5yQH8SKoboii0Y9z9YiMRNJL2BbWv0GvIEVRDaa7zTiFacDzXUBppCfqvipWdyedO8dMKqHNJPEBW6zdqDjGWVfzLzdjQQNXMWX2Ui0XZSMb2YLvvpOXAiCa4XMNcRzFPBP5l7zxFZNQ04WRU95dBCFTTxRkDXluUoZGDxhBSJ6sCPYu5gUjYaSkkDp5H4NZIiEUvvGGhgOXvKky078xA9RLDap8HQ66CybzqSf3rqEQomkUbvq5E,64BvkVvpFkevQhYIM2Fznqf1KCwzb3hudOgW1vSPpbfoKpStNXg3ZN8d2Nm3LfkkTeCeDhpYeFzm9RucB09FOElwbueIV4LoOmaLJWLv2rX3AJhuFbzxi05zFTUiz4CCouY99i0EcEos4ncyYDlpDfe9Rl8r2iKWkjj0xm50iq2eXnGmN2FWwZhZ9HswY4bvFp215qLkNCrqTzgftC9HCdpc7dJPANwkeH5jtbIixl5omuPTFU9ZkFO0mGyehMD5,Y9oFHfmY1PQpTUys2SuNvrkRLZ0ZEOTn5D8RV7BwDNVccWw3cz1WzmSVhEdZMQVkgl3eGT0Gyysg0hDq6yaGPZv93q8kYbssE6BeuU5zQkmhlLOAiWobXlhoap83dVjMD7a1dKTNgd1rvA5UwhgbrUm9DjjGeizLJaWO4T9e0tj7676r8d6LwMcs7vdYTCDTvlGVN8KKD7qcpTKD4rzK7sm9guvlrLdpip0ltQA0LvBeGhzcWA92oqkWR5hUQRyr,FJBMKmAa1xvYX13kTgdjKxptPYoXNRiIXZDfN3Ir4YD7MAhvkw5tA5NiFdh8cHod0O3wElkcwj0uIUttN0ZQA6VqYlgU7oMpjxT4nF1AHeRtrtgqPG4nb2wEGKcHrummXknUp79NSm16Gvofylua160ZOH1tawoK6IzFNArc5l7iTSurX2wRI7jGvQhKcCTtFqxTiBTxYA2UdUWAuJDVWDDuKFyKzPeTt2Zl7Tt3nrklr2ylTlVNjm8F5GchzKrT,Yx3hecmeqbqvNIgH57atjgWDgzbs5Gow0FqSXEWazEYItNmTSbcFHHU3xBjrcvMqJN6E3NJLIToWEmyjnVCkyTWN4vqn4ZLJEgejUxs0nUganj24L0xOusmPskrkAO0usdTHjj8hPaRy7N007LnKFgcdeq37TQ9JvaRuVDZx68W5RwDwOFnghy3AVhNty3W0QAy8TZaroL2F9hHwhrT5pDHHariEts8TholTVPV8Z876Hjc2hnbYEqkfdbDV5UFC,vZAwXiLWqpMRtMa74jKQrcYBhIzrLBXB4AJN9A3Xei6Urmotq36s3uyRyNd7wpnGOrOAIKrCZnT7p8l0rCWUUBJtXzBJ6kBUOUeFAsXgji9VSSUNeZ6oYJIIfUp5Fo7TOc0stjkkhUjO173iij7Cj3oAvOKGSsik7pMY58ZHIlOYdgtDhVtTmGP6mpvAQqXqesoOrJgagxe28CEBi4EwTWLUHYAZy9eiyTcRYjdoDhOf95Qe6cNggSw44Lx8nRWx,XXwe9LI7aRZX5vC84xDzFfCnCHqQZ1yA320TpXBCPWgHoUzDKHekJzyEbCkA67UmCiP31U0vYR7ycKwKgrhJD5XpTLSXgFwPcymMtltg8CTqmA7uiWKpSjVYBA9xy4qLSFOAtOhf2eQGq9Lfej9UPEhrUSUT48Cw1KEo65GPUWGuca5zyW7lgjn5TgOTeNxVBXK0Ij6GYHNsHKAmFCNVtq1gswKDUrXTppDMibS5VXy1gElDnfPzx1fDlgSWJ83Y,RWp0ynm2AE45YOwQfjCsBV4kaECVJ7NTkBlY2Nzc4ebmoS0JmBF8mhL8uYxywhQuDFQc022FWaDILvrsIDlrRXQ7SGhGdi0jTrOxCyUWV3ermGc7bTlqOxgHOdQ74a4TuuUtimxZFBfJJob13FCyGtI4Yg1opgDvegww88mdghbSAOfdI25Z672YrjvMkDspUSNdklTnQiWjBfaebJG44x308D6LqT35BJsqIEvIki6Cp7wuA26AA0doFtCmIYti,BTWv8h9PRmtkTnEOef0zgIDXKV0ycb25fqOXxifzqTkV97yO92kQ2JcfoYmDVmzhCSJR9lEDcMs4zRPjiOzyB1MUGae5eeY7gK389kjGqNU4IyyooRxNq23AHIJSkUWdNYw3comvmoAiDXbciOx8G7Wrld9Jfrb11DcZCeHdBqmduv7NENmsyca5CpV1b4ibSTl7V6U1K6eSEq4itFKLPfNf1ZjvCqXFfwAQI1bFHRDzQT3i7dzDRRS4roAFNxnQ,QGXAm2nsNbJ4GlHX3uoYN5ujg38qakSUNzXR9Qi6b7itw0vwYJeDug2GQL9oVFX6HbuEVtmtGwAuhIqtFCIRO0UHlzj5Mt7jFJyU4XzGGxNOHLZlMv1cQFBYijmGdGPWbau2GqV5ozsZWg30yRuUZcyJQWf7zIEgZusgiDueaWWeB5ntYV4Uf86ewsBaGz8jUpmB69Bq0qZhJFXfDyJIQST3smjq6SRgjs8p7CmWobR2GqoZu2bsfyH6Z9mN6Ss1,lAt9oU85v4HRaJ6ECmmozNF8lX2KlP7otqPExgc588OW98EMvfZVGVuZjrqwWqEMRlN3RmEbhkWCHYn1GYJtB1dPquzqShqlIGInEQHPN3mQHfqI428V5plenZnCAKPvXD14TS0YgdwtrqoIgkxAI9tc4HVAk3sDhT80LJkxaf1sLDxFxZGtpmN6kkxTMb15HL6G0599HupRGnJMz4cMydK7KZcrC4lzqN5d1ie3723E7LOB7d87MPGpG8djvIDN,DKQzGCtFHJk5EH1CImTD7lfLPrkwmzr1AZEdG56AEjQ2xVRJ3f0b3iJAidzVPArLgxPxtAl5K5mGduvJyctWhLtcp55bSiX0lYCSJKgLQqGHRiFD2KFu0g4NUyrFQuxy0wOLAEfz1jHUL9Fp0ePfQ0fA9yP3utymvSnUkIRfw1MgzMHfgCAWTGBWerj8cfxBKVuIOwS4mrkQMsQGjVFrFfGD1RBgLEfRs6C7uBZIhO1dYyzBWqUdMq0GukAhjA41,5lXsQnWYp4M2cAXLMLUkS0F2gjZz1stbXjr1i75kqZA4fx07cQQWZiCowYXQKmctqcdfCgGk8rWdRDi6YhWwdANuaMvaJ4UNtMNRFQQCW4QqVb6dCc3e678il7Iv6I1Sj9TAIm6pcASkbf3tQ1BA0h0mk5hjaRlToaiBtKK2ZrCAVNFuvtzACIz6lBJhaBdQVT8JRe0tYtia7ADWPXp6COtZ5SyAR3w58aYfIaFMN9E4uDuPEBBJgUb7hRCvUjpC,bcT45Q49EBzkWDYCwoCoyZd2lFxFxpv9fTFYK2OKLwnyKflNCZ95deU01oXLEhcNlVNAdPAhwUGSG25oXJCe88dKm3nVJwxQC0oe8lWFxK1hh8yp3WpGS7MTIthMRQ2GPv1BKZpQsbrWcc6jzZV2cECMsqnRobbBnP8wFALUptMCLqGOKatfMBK6s7vNHmgobfoX4KGybcvh8yLmQiUjBZVjyVZCJaivbBmmAoZbRpOMk9Dx4ZmnYSgsZ87coykb,Rd952GXBrAjWmE3JDA3lOeGFbBCmZe04MPYrqupUPpJe9cdGEPTvNs6TO4DdBcXakx0c1quM4Pw8wwAB3T3XyC2hSlqo9jhn29S9n9423kC8Z8T1escqRhEyh2ua1l7IyNEi9PoINVKiJUkt4ufTgcYlqYKgRTTJASX5nbppV8ShVBG3s93mwCLrNyzYG528BHedtHDvZcuOihknsac7U5UbvpreN0hmqoxRiWEsHiiCjP5xtcIedXVh1MuCymA6,CNEbTWnIvGXvCItfeSZQVkCIAMREGLzKDCpTL6oig967RkdNLxpgVkYqXJwOhTzRtZgd5xulJjItQqn3ijHP5KITBmtNr6fcnhHgCzxVV6PGgEpN87Whb0sKFRAql2rt9PqNp8HVPPDrBBvw8yaO49t1VtKN1M2CDBQFhpr4AtEIHuoprVqj6CrRTsJ0o712lIk4OJODfrXvcAcRnUgmlNaTUHQZd29pD5RwI7jRgTixsbUUUZJ9f4qsmpIF1uz7,uM08SsWsda2jkMVQVKma63w6weOg8QXxTLL5HDQarRvGHFzDUEFa0nCagl4vsu7RgcsKRqF8o95UyckB9QiDUqEitAXgFt9V9URlJKf6F77HQ1sxdQZHDqmFcUZRUHRFG7KQBruLv5YAD9C6PaJ6uTYtGFT4AG2s7hv6zrnGhIkqJaFWua4bsX4hndJONpGtLe9u3dHCtPoxVFGJwplKytb6zqdilHHYbbE1M49IeMtfpxrzQwsf0p6rnfEUat5A,ySGSy5AJ3T1c5b8Oj3fUwj5rN17dLFz4pcun6homZRBg4Iyg7EXXHnIrwnEwiDXdKq7fjSxV7AdcDQ6e5kVNSPPd5CHR9tamrPQ7ep95TolXmfcCUXnz3q9WU2ZRXF8B0FSecAcqJxsVJBojIGeJ1l2rKd2UZrv03l5kdUgeKg0U5Xy9x9m9JJ5UIMphd993YQXIbDuJUYHdaEnRG0BZlG7e9m3t0f6OEowk17Q6qv8viL76c8W4aU8uSEWsxeoN,fCKYOpXbC0g2pUT1Nbn2AcDFfmJQHDiyS2SaCYsDND3OwYysz7OT3JQOr8flUW1tpdOYuEIYMbzWDaJacuZfyip39csVhgYTTByQm9MPrnzB86kIJi0DiavgpCMskPM1m533DwmDOXmYMOHDxRNWon0f3yd4K3lMSdIeTa5N3cm87N7Gz5jPdny3RTMTAWZVzwxfB32CHHnn0zmGcVZNXN2Ri3F1my98g0XBuSFoHJ4BnUfHFWTz7tC3B1KgOKDy,F1c6pfBUcdm29XYEcXviZbvZJV8mlH4h4COqqQJnmteuA9UqVeBmOp1nGE11wQs4cMJ7rFK2RIZd9etOOsadxfep8vVqzhub3XhS3sgX66oD6dvsJihJnCHCK92Rby3C1sSHQ3yAPTV7D87z2RWtalH5nH7uHaYUxslyWAfSzfVcqtwf1tygCgwc4IeUxROPLB96bn6VtiKzJKdBYOATmKklmzBNH7gLIKslQPFfA6EHoUGCbO6fyoB6qNJr0suf,5kYjeM6btIWGt0wlnOMIKGVdhymh8x88p36cBVV8vEnAs9EVt4IeyHSGQ6vpqd7GQUBJvGSdG8myJqr0ShsqPn5nmVdtgnlBeqKweQI0il6O53lODJemR2lYVqDdNS3eKQqyYGXEOM2rlW9wwx8RYuYBXLg5ACf1MAgSnXKEujS9HOWZLO8UMWIrJbMcJsuH2GtaAb74MhQu23jBuQMjvEFba9W67duScj2VlLvxAEpisYtzHvCFVsmoHHIybyuP,tEaR0hLP9pzLSgYSoYXqXNnnJZVnMmHNIRTxnnCYJTCdZvmf5UYFtTmLTs7a0TqdKTtgKiz41fbT4sfzDYW3z8Jrv66TmXWWGMMwFZkfBWNGF3NyCyGbwuZrsuAWWi7oR522ctrd7n366U0wTBFYQJOhs0uXQXJ7xCSjXHOdgZRbqcml4O9CoCd7gOxN5DwMhVv7mxO4rmFk08KPIVhwnzmAl7BlLLkMKjpZ3DzYt531rZZHFHo14eJLs3rpLDsA,8CfG01DzWQ5iyyHPnWQgg8ihtKr3oyFfkNRsrK2SUEZdkpaqz6hVMuM0xbWY3xVcWZ9mXeCce9QCcMLmeo6aYoeQ0gIVh1xMq3F7iniIj6UWt9IJdmk3QXMCEmWUjiRdzmpiIXzv4zX7bQIMTrVUrRlnRrtn8M6gOXPAMNrDPTPg5vyzAHX1IZb0WuNKGnh4405uQSdxxvbCbyZFZuNSTSRDVGsfTRALy8V93CxDJ0ndxSikqJUxG0B1bE1A1CL4,tItf41btxFapros33cC7RiaaLX7pP3CBDgKcYpA1vysqtmjrSho3Dx8P7OFsELKHT68DZJI6KLfkaC2eScgAjekAOIanaO1y1bNrE6ldJdtK5ugAWVM7aAzR815CTDsn3cYkTaVeF91YEYboVTLVAwLqRke6VA2tFfjlI8IuZhKdArzi4FmQp8lhs3fPHAt98RheqJvNTividPMlozDeHmhKdps4AJsTg88GNiEEBm4Nm7JPFsz5SdOoDBSQskOT,bH52xEw7fWxvAg3CSmstFhKjoJMeVxwt7Fv0qBqYa8fqajo4ZZKqrRY8Ti5gf9lfiCPVRuliyxhzUR7rh635xp081pyvkwcXKJuaDCiAh3O9lAC0f7hqLAHiA7VrUsIK1uzDOhcZmg2yfgaM0yEEz9NCOSw9k36ER8A1b3vJglTRM6NDaElu1a8WsA3Bofg2OnW6xDeYcEayR9ozjGQi5lyHgmy1jajye20iaH6hxckdUOlUmVhdzyKyoFZlBK3z,NsDeEiNMY7OuyPxlKdQRcYBrMfkjo9WzKDaqdr2fkj8f24mvTrlzhTxEhbQqchaevpL1cSDM24Ikb42FqN9hrGExV0bke8OndRvZSzTFU2w4fQg0h7fKXW6Wi8AFzoynYfydWgdzDm5wVZpijUd7zotr8Vj4xmCh08oPiF5ec9AX9YaS3HTyGdMYzsJQruAwfMAkyOVQ1s3WERlvwlwhD7AzoOcbKqc3zhN6B86ghzmPqW2DoquxNPKzu5XQpHof,1CnHqfqO3sTPM3w2BtBTyoPleKE0bK9yzsti6u1eJAlrop3gy2rGtHiSpjPhQ8vW7o6888VO310I97JpdMIaBjmoAb7Bw1mEiYxY3pJWL50NQ7Qkb72oOmffDhEA1bywneVp5dukuhkNSfNuIJfMorcoTdD17aI4DRCE1eBfPp8qbcJiKStEFoAFOHED72MDqK8zcQRRo7MDrLMdg9slfS8BkFRT5oQ2hSzqu8PU3WrWCPvUrR7GtVZ0aMVFDwX3,4zn5aEune7nLQvfbae069nw4Bi4AoJ26GcMKeQIMzp5tPxxqdjxLvvnqMB5sPBDqReOykq6zvkCyU2lvN1ZfQ4n6DCbiTAgmy7tE7MpOKtWF6Gi2i0LiJEECObjIsynHDjFb7TOm2Mkkq1sjj1kF5LiKQ2Qpsylxo30F1XyTxn8I33UC6muWoz5G3cGqwBpCFb8cjwXG4QT2q5W51JsD01RISORfgrMrWCu8eVA6olw4x6MPWXjNsmvPAyIlIGKx,UWoP4pceuRAe2Iuo12DH8X6OV9ra1RnL9ULFTyFxlsdCZueCzO7bXDQ9cxSDKTIoXq08tAN1N48QJBuWg9lmAZcYVAk9nWJfSpX1VSaQxosn94qqiqVE1AD8Oq5lPsWLghUcO4qsQWyQeRdoClIRcDkwyRyd9Z55bo8deEdArMlZpde23CH8pefEKKZav5Lq9FfA9w1URqXFxkcJfJL3vnlzyRpKiCnSqf7KjbnEAcHyAgazXfJo9dtHD2fNDHVs,EcF2HiMBicvzdcKZ72xcG9eRSdlXc7K81uh4rwNgErJglmdX9EUsrH4yQH13JEPmgPvMHxv8QtBAT6FUtlndUjgRKx36BkBumslBydcNqx3QqJ1OpQxBpWykAecex66cIDa2FXAAMBaDmWfRdMwAIjOzM63uTd8mDQvpyJ6chzjUR4p324xyQSX8L0SgCoRyKdrW4nC1t1uorRQyVcGWsDIE2ijpZ3iqVzwpADSfolR6Ie6iRc7wHLn6p4p2CAXD,IkRxKXhJZi5shDziL5BqE6wX5VmpXVB21yw7YR850DbH7aKffcds6IqVgW3jCl67oOIKOY5neWaAPp6S4GhONbs498HQJkBa3VmoTgl7sIEdp8g0XQOcl0ffs7FWX7TkzCv05qnNQNNkiwx7PgkCTDgBMTkhwN1mSAvPboPcj85y3w9IVFDjfyjEeWrae0E0ZR4oQaZLFqwC1QEcNoto1Gjf8d1BPEx17oj0xhAix3Eqb5tB3OCZOvfDQYPNCIL3,kaTyLItequQFx7Lv8rgHMlrg9BeRjmHBYeeVfEM8usN0sacweO7cQhaxejDhGBMvaQnO4293G8ypcMFqo7iAocoaIxcJf8qv43hNwLNUn21uYac3BZYtRwqj5rUBEtuWFQPmrWGbeHR54eMjizCHEWSkrgkMu6btouJgxlNptYaS7Js7uGOAqVguzG3ari14BHQ2p2s8JRQZ8QSMEjC1FNnXykv9Sk6JfbTjHw6F3dE3OBbmpQzqqDhQeJIgqn5i,b9Tyj97vayjyiU4aLYHHsk0gvHwhi3oJT3JDDvHbo9mypEDX8n0fkNhdbXLN0YMJ71izbxhw3WAdPy'
2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [9]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:44:07 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
,[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:44:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C91ADCD2-C046-4AA4-A330-A15E9E6C4C01
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57412
[ThaliCore] Session.disconnect() p,eer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B945E962-8119-4EBA-AB34-F0EB503CB59E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C91ADCD2-C046-4AA4-A330-A15E9E6C4C01", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:B945E962-8119-4EBA-AB34-F0EB503CB59E
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A
,2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3F4B435F-5E0B-4866-9A20-B919CF8A,1E0D
,[ThaliCore] Browser.startListening
,2017-07-21 08:44:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:44:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"B73B52DC-F7A7-4412-9E88-BAB14F24676C","generation":0}'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for B73B52DC-F7A7-4412-9E88-BAB14F24676C (syncValue: uKrkrEHR0iiVsXk7uXkMSmKll4PJiqoS)'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F2,4676C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14", generation: 0)
,2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14","generation":0}'
,2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
2017-07-21 08:44:09 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A","generation":0}'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPe,er:withDiscoveryInfo:) found peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A", generation: 0)
,2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","generation":0}'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:09 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,3B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,3B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,3B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CAFF37F6-0BEE-47FB-9C0F-1AC0055BDE14", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:B7,3B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:B73B52DC,-F7A7-4412-9E88-BAB14F24676C error: max retries exceeded
2017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"uKrkrEHR0iiVsXk7uXkMSmKll4PJiqoS","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'uKrkrEHR0iiVsXk7uXkMSmKll4PJiqoS', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"B73B52DC-F7A7-4412-9E88-BAB14F24676C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"B73B52DC-F7A7-4412-9E88-BAB14F24676C","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 08:44:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A (syncValue: b0PRgU0,w6WO8mmk7jDX1gxC83KHi25ip)'
2017-07-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:60053FDE-BFCB,-4C56-8D5A-7D3EF3F5C45A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:B73B52DC-F7A7-4412-9E88-BAB14F24676C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "B73B52DC-F7A7-4412-9E88-BAB14F24676C", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57433
2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b0PRgU0w6WO8mmk7jDX1gxC83KHi25ip",,"error":null,"portNumber":57433}'
2017-07-21 08:44:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'b0PRgU0w6WO8mmk7jDX1gxC83KHi25ip', error: 'null', listeningPort: '57433''
,Connecting to the localhost:57433
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [10]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:57433
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-21 08:44:23 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 []
,# teardown
,2017-07-21 08:44:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:0C7FFC21-A2BF-4C15-B36D-7F2D7E19D22A
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57433
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A", generation: 0)
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"b0PRgU0w6WO8mmk7jDX1gxC83KHi25ip","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:23 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:60053FDE-BFCB-4C56-8D5A-7D3EF3F5C45A:0
,[ThaliCore] BrowserRelay.deinit
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E0B635E3-F14B-483A-B337-CC90A5ACF439
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:44:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:44:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:27EE564A-9F54-4624-AB03-96C97755C207
,[ThaliCore] Browser.startListening
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:44:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","generation":0}'
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 36797C19-C4DE-4D06-8AE0-EA5972815BBE (syncValue: 4xDFigGYQSpIXmWtnuLfCb94dCTtBhv3)'
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}'
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:44:25 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E0B635E3-F14B-483A-B337-CC90A5ACF439:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E5BE70F-136E-443D-9F11-E27DA37D9C01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E5BE70F-136E-443D-9F11-E27DA37D9C01", generation: 0)
2017-07-21 08:44:26 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5E5BE70F-136E-443D-9F11-E27DA37D9C01","generation":0}'
2017-07-21 08:44:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:26 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:44:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,6797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,6797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,6797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:36797C19,-C4DE-4D06-8AE0-EA5972815BBE error: max retries exceeded
2017-07-21 08:44:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4xDFigGYQSpIXmWtnuLfCb94dCTtBhv3","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:44:36 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4xDFigGYQSpIXmWtnuLfCb94dCTtBhv3', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:44:36 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 08:44:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 08:44:36 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:36 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:44:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 741F0AA8-1BCC-4724-89EE-9E3D1B5337DF (syncValue: xWtEsiI,eZ6yUX5D7QEj9Is9eOgpnHXNy)'
2017-07-21 08:44:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:44:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:44:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3
[ThaliCore] Advertiser: session connected Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57448
,2017-07-21 08:44:39 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xWtEsiIeZ6yUX5D7QEj9Is9eOgpnHXNy","error":null,"portNumber":57448}'
,2017-07-21 08:44:39 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'xWtEsiIeZ6yUX5D7QEj9Is9eOgpnHXNy', error: 'null', listeningPort: '57448''
,Connecting to the localhost:57448
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
,Connected to the localhost:57448
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [11]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-21 08:44:39 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:11 []
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3
,[ThaliCore] Session.session(_:peer:didChange:) peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3
[ThaliCore] Session.startOutputStream(with:) peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,2 [12]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (1237 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (5191 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (2545 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (2119 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (2261 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (22528 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received (11253 bytes):'
,2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-21 08:44:42 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID,:12
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:12 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
,2017-07-21 08:44:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:44:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E0B635E3-F14B-483A-B337-CC90A5ACF439
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57448
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "E0B635E3-F14B-483A-B337-CC90A5ACF439", generation: 0)
,[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xWtEsiIeZ6yUX5D7QEj9Is9eOgpnHXNy","error":"Session disconnected","portNumber":null}'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:42 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:A50A417B-DF3C-40A7-A46F-BFB83247D5B3
[ThaliCore] Session.deinit peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserRelay.deinit
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3D2136C9-A712-40E2-AB5D-6EDA6346155A
[ThaliCore] Browser.startListening
2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:44:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9DF51D,A4-C820-4929-9B7F-F9FC8ADF5DD7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7
,2017-07-21 08:44:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:44:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:44:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E5BE70F-136E-443D-9F11-E27DA37D9C01:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E5BE70F-136E-443D-9F11-E27DA37D9C01", generation: 0)
2017-07-21 08:44:44 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"5E5BE70F-136E-443D-9F11-E27DA37D9C01","generation":0}]'
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"5E5BE70F-136E-443D-9F11-E27DA37D9C01","generation":0}'
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
2017-07-21 08:44:44 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03:0
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"741F,0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03", generation: 0)
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabili,tyChangedEvent due to not being in started state'
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","generation":0,}]'
2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","generation":0}'
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03","generation":0}]'
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"69DEB6CB-9101-44A3-A4F2-AEE6F73A7B03","generation":0}'
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5E5BE70F-136E-443D-9F11-E27DA37D9C01:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5E5BE70F-136E-443D-9F11-E27DA37D9C01", generation: 0)
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"5E5BE70F-136E-443D-9F11-E27DA37D9C01","generation":0}]'
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"5E5BE70F-136E-443D-9F11-E27DA37D9C01","generation":0}'
,2017-07-21 08:44:44 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9DF51DA4-C820-4929-9B7F-F9FC8ADF5DD7
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityCh,a,nged registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-21 08:44:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7FBBC285-D19C-4443-AB5D-F40BB1FD7C67
,[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
,ok 106 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BCEF7AF1-F7D9-40EE-9598-878F79B53331", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BCEF7AF1-F7D9-40EE-9598-878F79B53331
,ok 107 discoveryActive should be false
,ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 109 discoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BCEF7AF1-F7D9-40EE-9598-878F79B53331
,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-21 08:44:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 08:44:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-21 08:44:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-21 08:44:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-21 08:44:53 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-21 08:44:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-21 08:44:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-21 08:44:55 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:56 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:a5d474a9-58ea-45b5-94c0-97ce6952e507 error: startListeningNotActive
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"KlRgvwta062vo6l3EzFDlCiTkR8kw8Qe","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort ,is null
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"a5d474a9-58ea-45b5-94c0-97ce6952e507","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:44:56 - DEBUG t,haliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"a5d474a9-58ea-45b5-94c0-97ce6952e507","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1D91C4AB-8683-4498-8AFF-FB50CB7E3529
[ThaliCore] Browser.startListening
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on star,ting
ok 132 Got null as expected
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Bq6B4YWdb2FEHWLeBNGswCkT1idgSb99","error":"Illegal peerID","portNumber":null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
,ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","generation":0}]'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","generation":0}'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}]'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-21 08:44:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B3FBBD79-1373-42D0-9FB9-58E1AC7CEC07
[ThaliCore] Browser.startListening
2017-07-21 08:44:57 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:44:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on star,ting
,ok 138 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:8977d02f-14db-4cc0-9e71-adde278c9928
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:44:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:44:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:44:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:44:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB
2017-07-21 0,8:44:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:44:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4CE93326-06BD-4BD0-BBF6-EB7F10B89AF7
[ThaliCore] Browser.startListening
2017-07-21 08:44:59 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:44:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:44:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startList,eningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
2017-07-21 08:45:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","generation":0}'
2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 36797C19-C4DE-4D06-8AE0-EA5972815BBE, (syncValue: Cx9F2TSCo8FvzDRz9M6eu7OyNN7RDOAI)'
2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA59728,15BBE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:,) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPList,ener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"741F0AA8-1BCC-4724-89EE-9E3D1B5337DF","generation":0}'
,2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
2017-07-21 08:45:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"66D54677-E5CE-4872-AF60-920DE29F35DA","generation":0}'
2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:45:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
,2017-07-21 08:45:01 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"42482938-AF2F-480B-B29A-69D1D0864D42","generation":0}'
,2017-07-21 08:45:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:01 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,6797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:741F0AA8-1BCC-4724-89EE-9E3D1B5337DF:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "741F0AA8-1BCC-4724-89EE-9E3D1B5337DF", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,6797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:90256AE2-A1A8-41AF-8741-55727912E1A1
[ThaliCore] Advertiser: session connected Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:90256AE2-A1A8-41AF-8741-55727912E1A1 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C
[ThaliCore] Advertiser: session connected Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:36,797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,6797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "36797C19-C4DE-4D06-8AE0-EA5972815BBE", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:45:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Cx9F2TSCo8FvzDRz9M6eu7OyNN7RDOAI","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:45:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Cx9F2TSCo8FvzDRz9M6eu7OyNN7RDOAI', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:45:08 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:45:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"36797C19-C4DE-4D06-8AE0-EA5972815BBE","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
,2017-07-21 08:45:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:45:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 66D54677-E5CE-4872-AF60-920DE29F35DA (syncValue: Snl9OXWYLXbaghUNABkSTpsoUYCgPSML)'
,2017-07-21 08:45:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:45:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:36797C19-C4DE-4D06-8AE0-EA5972815BBE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:90256AE2-A1A8-41AF-8741-55727912E1A1
,[ThaliCore] Session.session(_:peer:didChange:) peer:90256AE2-A1A8-41AF-8741-55727912E1A1 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:90256AE2-A1A8-41AF-8741-55727912E1A1
,[ThaliCore] Session.startOutputStream(with:) peer:90256AE2-A1A8-41AF-8741-55727912E1A1
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [13]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57464
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Snl9OXWYLXbaghUNABkSTpsoUYCgPSML","error":null,"portNumber":57464}'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Snl9OXWYLXbaghUNABkSTpsoUYCgPSML', error: 'null', listeningPort: '57464''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [13, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0) found active relay
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"N5HesuwBVoK1D6Spawxv5XTOGuRvdTRR","error":null,"portNumber":57464}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "66D54677-E5CE-4872-AF60-920DE29F35DA", generation: 0) found active relay
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7rnE4a3eY7OP0kjoAtq3PNkyK2puYQtf","error":null,"portNumber":57464}'
,ok 147 No error
ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C
[ThaliCore] Session.startOutputStream(with:) peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [13, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:45:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:45:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B9F325A6-C7EE-4930-9B90-2AB7F638F9EB
2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:45:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:66D54677-E5CE-4872-AF60-920DE29F35DA
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57464
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectH,andler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeS,treams() vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] Session.disconnect() peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:14 [13, ,15]
[ThaliCore] TCPListener.deinit
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [15]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 []
,[ThaliCore] Session.session(_:peer:didChange:) peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C
,[ThaliCore] Session.deinit peer:66D54677-E5CE-4872-AF60-920DE29F35DA:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:90256AE2-A1A8-41AF-8741-55727912E1A1 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "B9F325A6-C7EE-4930-9B90-2AB7F638F9EB", generation: 0)
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,# initial peer discovery
,2017-07-21 08:45:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,[ThaliCore] Session.deinit peer:CCDA5488-0FE9-49FD-BE79-9B15BFA4EF8C
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:12 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-21 08:45:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-21 08:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-21 08:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-21 08:45:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:13 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:14 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-21 08:45:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:45:14 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-21 08:45:14 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:14 - DEBUG createNativeListener: 'listening 57468'
,ok 149 Should throw
,# teardown
,2017-07-21 08:45:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:14 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'listening 57470'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'listening 57473'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'listening 57477'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client co,nnection to node - 0 - 0 - closed'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP cli,ent connection <-> Mux - 0 - close'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'listening 57482'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
,ok 161 incoming remains open
,# teardown
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - close'
2017-07-21 08:45:16, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'listening 57486'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:16 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'listening 57490'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'listening 57494'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-21 08:45:17 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'listening 57498'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-21 08:45:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-21 08:45:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 08:45:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:19 - DEBUG createNativeListener: 'listening 57550'
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-21 08:45:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:45:20 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'listening 57554'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 186 we should not have gotten an error
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 188 server should be fine
,ok 189 server should be open
,ok 190 incoming has been removed
,ok 191 The mux object should be closed
,ok 192 The mux stream should be closed
,# teardown
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:20 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'listening 57557'
,ok 196 port must be in range
,# teardown
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'listening 57558'
,ok 197 second start should return same port
,# teardown
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-21 08:45:21 - DEBUG createNativeListener: 'listening 57560'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 198 we should be connected
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 199 now we are disconnected
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-21 08:45:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:21 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-21 08:45:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 200 Passed bogus id
,2017-07-21 08:45:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-21 08:45:22 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 57562
,ok 207 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:45:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DE913D1C-0249-4CCF-AF63-177E5F6EFB18
2017-07-21 0,8:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B38FB079-FA3C-4C03-AC60-04EEE3967772
,[ThaliCore] Browser.startListening
2017-07-21 08:45:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:45:22 - INFO thaliMobile: 'Received state ({"discoveryActive,":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:22 - INFO thaliMobile: 'F,iltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
2017-07-21 08:45:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"42482938-AF2F-480B-B29A-69D1D0864D42","generation":0}'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 42482938-AF2F-480B-B29A-69D1D0864D42 (syncValue: FzQy5MSjs1gZ6pDAJRAjEfGXH7XVjUbx)'
,2017-07-21 08:45:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
2017-07-21 08:45:23 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"0518CF61-E252-42B9-9611-C4C458B9CB70","generation":0}'
2017-07-21 08:45:23 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:23 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
2017-07-21 08:45:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F178AC04-DA74-48EA-963C-5633E8815F6D","generation":0}'
2017-07-21 08:45:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:24 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:45:24 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DE913D1C-0249-4CCF-AF63-177E5F6EFB18:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,2482938-AF2F-480B-B29A-69D1D0864D42", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,2482938-AF2F-480B-B29A-69D1D0864D42", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] Session.deinit peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:42482938-AF2F-480B-B29A-69D1D0864D42:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:42,482938-AF2F-480B-B29A-69D1D0864D42:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,2482938-AF2F-480B-B29A-69D1D0864D42", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "42482938-AF2F-480B-B29A-69D1D0864D42", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FzQy5MSjs1gZ6pDAJRAjEfGXH7XVjUbx","error":"Peer is unavailable","portNumber":null}'
2017-07-21 08:45:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolve,d -syncValue: 'FzQy5MSjs1gZ6pDAJRAjEfGXH7XVjUbx', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"42482938-AF2F-480B-B29A-69D1D0864D,42","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper:, 'Received peer availability changed event with {"peerIdentifier":"42482938-AF2F-480B-B29A-69D1D0864D42","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-21 08:45:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityC,h,angedEvent due to not being in started state'
,2017-07-21 08:45:31 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-21 08:45:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0518CF61-E252-42B9-9611-C4C458B9CB70 (syncValue: l0D9QZ23EYSPV8OEr5niTGUMgRZTzGo6)'
,2017-07-21 08:45:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:45:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:42482938-AF2F-480B-B29A-69D1D0864D42:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57574
,2017-07-21 08:45:35 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"l0D9QZ23EYSPV8OEr5niTGUMgRZTzGo6","error":null,"portNumber":57574}'
,2017-07-21 08:45:35 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'l0D9QZ23EYSPV8OEr5niTGUMgRZTzGo6', error: 'null', listeningPort: '57574''
,ok 210 should be equal
,2017-07-21 08:45:35 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F178AC04-DA74-48EA-963C-5633E8815F6D (syncValue: FwCTiNSqZ6vUnHMFXBnx96wiYbSv3nXZ)'
,2017-07-21 08:45:35 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C
[ThaliCore] Advertiser: session connected Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57578
,2017-07-21 08:45:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"FwCTiNSqZ6vUnHMFXBnx96wiYbSv3nXZ","error":null,"portNumber":57578}'
2017-07-21 08:45:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'F,wCTiNSqZ6vUnHMFXBnx96wiYbSv3nXZ', error: 'null', listeningPort: '57578''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9
[ThaliCore] Advertiser: session connected Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C
,[ThaliCore] Session.session(_:peer:didChange:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9 state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 ,08:45:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-21 08:45:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DE913D1C-0249-4CCF-AF63-1,77E5F6EFB18
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:45:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,[ThaliCore] BrowserManager.disconnect peer:0518CF61-E252-42B9-9611-C4C458B9CB70
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57574
[ThaliCore] Session.disconnect() p,eer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:F178AC04-DA74-48EA-963C-5633E8815F6D
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57578
,[ThaliCore] Session.disconnect() peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE8BE39E-B612-4A41-A856-2534FC139BD9 state: connected -> notConnected
[ThaliCore] Session.session(_:peer:didChange:) peer:ECE08B35-69CF-4E20-AC7F-DB502725995C state: connected -> notConnected
[ThaliCore,] Advertiser: session notConnected Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] Advertiser: session notConnected Peer(uuid: "DE913D1C-0249-4CCF-AF63-177E5F6EFB18", generation: 0)
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:CE8BE39E-B612-4A41-A856-2534FC139BD9
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 08:45:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:45:46 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 57580
,ok 212 should be equal
,ok 213 should be equal
,ok 214 should be equal
,# teardown
,[ThaliCore] Session.deinit peer:CE8BE39E-B612-4A41-A856-2534FC139BD9
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:45:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21, 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:0012F678-84C7-457A-A520-2401E6F33249
2017-07-21 0,8:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ED34D69B-9B8A-4289-B861-3ADB0758843A
[ThaliCore] Browser.startListening
2017-07-21 08:45:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,",advertisingActive":true}'
2017-07-21 08:45:47 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:45:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"0518CF61-E252-42B9-9611-C4C458B9CB70","generation":0}'
,2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0518CF61-E252-42B9-9611-C4C458B9CB70 (syncValue: zw4B3701zgxp1JCrXKCJGsV42Z3uK3Zl)'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F178AC04-DA74-48EA-963C-5633E8815F6D","generation":0}'
,2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:48 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
2017-07-21 08:45:49 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}'
2017-07-21 08:45:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-21 08:45:49 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-21 08:45:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,2017-07-21 08:45:49 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0012F678-84C7-457A-A520-2401E6F33249:0
2017-07-21 08:45:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "001,2F678-84C7-457A-A520-2401E6F33249", generation: 0)
2017-07-21 08:45:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:49 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:05,18CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:05,18CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
,[ThaliCore] Session.deinit peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:05,18CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0518CF61-E252-42B9-9611-C4C458B9CB70", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"zw4B3701zgxp1JCrXKCJGsV42Z3uK3Zl","error":"Peer is unavailable",,"portNumber":null}'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'zw4B3701zgxp1JCrXKCJGsV42Z3uK3Zl', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"0518CF61-E252-42B9-9611-C4C458B9CB70","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0518CF61-E252-42B9-9611-C4C458B9CB70","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:45:56 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-21 08:45:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F178AC04-DA74-48EA-963C-5633E8815F6D (syncValue: gXkOoNVnm3x7EpknSr8H61l,rESANWW5S)'
2017-07-21 08:45:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F178AC04-DA74-48EA-963C-5633E,8815F6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:45:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:45:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:0518CF61-E252-42B9-9611-C4C458B9CB70:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F1,78AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:86F951D8-EEC1-4408-BE41-8D2039509318
[ThaliCore] Advertiser: session connected Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:86F951D8-EEC1-4408-BE41-8D2039509318 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F1,78AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:86F951D8-EEC1-4408-BE41-8D2039509318
,[ThaliCore] Session.session(_:peer:didChange:) peer:86F951D8-EEC1-4408-BE41-8D2039509318 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F1,78AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F1,78AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:F178AC04,-DA74-48EA-963C-5633E8815F6D error: max retries exceeded
2017-07-21 08:46:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gXkOoNVnm3x7EpknSr8H61lrESANWW5S","error":"Connection could not be established","portNumber":null}'
2017-0,7-21 08:46:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gXkOoNVnm3x7EpknSr8H61lrESANWW5S', error: 'Connection could not be established', listeningPort: '%s''
2017-07-21 08:46:07 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"F178AC04-DA74-48EA-963C-5633E8815F6D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-21 08:46:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-21 08:46:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F178AC04-DA74-48EA-963C-5633E8815F6D","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-21 08:46:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-21 08:46:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-21 08:46:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 1D07C8CF-1737-4DDE-9F61-B35248B29157 (syncValue: WZwfYoo,YMiZls3xkwvfEG41FV1fikRkJ)'
2017-07-21 08:46:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D07C8CF-1737,-4DDE-9F61-B35248B29157:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:46:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-21 08:46:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3
[ThaliCore] Advertiser: session connected Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57603
,2017-07-21 08:46:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"WZwfYooYMiZls3xkwvfEG41FV1fikRkJ","error":null,"portNumber":57603}'
,2017-07-21 08:46:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'WZwfYooYMiZls3xkwvfEG41FV1fikRkJ', error: 'null', listeningPort: '57603''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-21 08:46:10 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 184ABA8E-200B-45B1-B43C-D18C7DCD96DA (syncValue: HIeI49G9a6QyZznPKhxUv1J4FBCGSle1)'
,2017-07-21 08:46:10 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-21 08:46:10 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57609
,2017-07-21 08:46:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"HIeI49G9a6QyZznPKhxUv1J4FBCGSle1","error":null,"portNumber":57609}'
,2017-07-21 08:46:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'HIeI49G9a6QyZznPKhxUv1J4FBCGSle1', error: 'null', listeningPort: '57609''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F178AC04-DA74-48EA-963C-5633E8815F6D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F178AC04-DA74-48EA-963C-5633E8815F6D", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:46:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:0012F678-84C7-457A-A520-2401E6F33249
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:1D07C8CF-1737-4DDE-9F61-B35248B29157
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57603
[ThaliCore] Session.disconnect() peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57609
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3
[ThaliCore] Sessio,n.session(_:peer:didChange:) peer:86F951D8-EEC1-4408-BE41-8D2039509318 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "0012F678-84C7-457A-A520-2401E6F33249", generation: 0)
,[ThaliCore] Session.deinit peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserRelay.deinit
2017-07-21 08:46:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai,labilityChanged registered to native'
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered ,to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:5D28A721-C94F-4EC6-A111-4D328F7EB6A3
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:16 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:17 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'listening 57613'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 227 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 228 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 229 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 57614'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CCBB82C0-3995-4EE5-A97D-77FD6406D0D9
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
ok 230 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Received, state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 231 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
,# teardown
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}]'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'listening 57615'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3463371B-8A3B-4BF4-85DD-0346D178DCE3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3463371B-8A3B-4BF4-85DD-0346D178DCE3
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 233 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3463371B-8A3B-4BF4-85DD-0346D178DCE3", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:3463371B-8A3B-4BF4-85DD-0346D178DCE3
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3463371B-8A3B-4BF4-85DD-0346D178DCE3
,[ThaliCore] Advertiser.stopAdvertising() peerID:3463371B-8A3B-4BF4-85DD-0346D178DCE3
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 235 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'listening 57618'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 238 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 239 network status should have certain non-empty properties
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:19 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-21 08:46:19 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
,ok 241 specific error expected
,# teardown
,ok 242 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:20 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'listening 57619'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7CCB5A3E-B39E-40F3-976E-99D20FFDDA60
[ThaliCore] Browser.startListening
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserM,anager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "CAC986F8-969E-4169-BC3D-7DEC6921A18A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:CAC986F8-969E-4169-BC3D-7DEC6921A18A
2017-07-21 08:46:20 - DEBUG thaliM,o,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started",:false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:CAC986F8-969E-4169-BC3D-7DEC6921A18A
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 244 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'listening 57622'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F984FDFD-68EC-4640-AF6C-F998D5EE2D35
[ThaliCore] Browser.startListening
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EB64C264-2D06-49FE-9EDC-933605F22F0F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:EB64C264-2D06-,49FE-9EDC-933605F22F0F
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"adve,rtisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out ,discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
2017-07-21 08:46:20 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D07C8CF-1737-4DDE-9F61-B35248B29157:0
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7D,CD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D07C8CF-1737-4DDE-9F61-B35248B29157", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:EB64C264-2D06-49FE-9EDC-933605F22F0F
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08,:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-2,1 08:46:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}]'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","generation":0}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,# all services are stopped when we call stop
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'listening 57624'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8463E3A0-8582-4AA7-9701-4B316B746B9B
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8B6993FF-9DC1-4487-A31A-FFB249AA7F0A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:8B6993FF-9DC1-4487-A31A-FFB249AA7F0A
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:8B6993FF-9DC1-4487-A31A-FFB249AA7F0A
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 08:46:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21, 08:46:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 247 is stopped after calling stop
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:46:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,ok 248 connection should fail after stopping
,# teardown
,ok 249 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-21 08:46:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:21 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:21 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 251 error description matches
,# teardown
,ok 252 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-21 08:46:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 254 error description matches
,# teardown
,ok 255 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 256 IMPLEMENT ME!!!!!!
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-21 08:46:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:23 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-21 08:46:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 259 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-21 08:46:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 260 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-21 08:46:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:24 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 262 NOT IMPLEMENTED # SKIP
,# teardown
,ok 263 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-21 08:46:24 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:25 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-21 08:46:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 265 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-21 08:46:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 266 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:25 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-21 08:46:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 267 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'listening 57627'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BB0F13C9-60C3-4B80-8175-A2F40C7AFA8E
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
ok 271 advertisingActive matches
,2017-07-21 08:46:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'listening 57628'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D11CAE76-4115-4F31-98F9-72BD19F4E839", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D11CAE76-4115-4F31-98F9-72BD19F4E839
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 discoveryActive matches
,ok 273 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D11CAE76-4115-4F31-98F9-72BD19F4E839
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'listening 57630'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 276 must be stopped
[ThaliCore] BrowserManager.stopLi,steningForAdvertisements()
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'listening 57631'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8C92CBD2-7B88-49A4-A88D-CC75B7C32A89
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "00001AB7-B22E-4EDB-B2BA-912191A724A6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:00001AB7-B22E-4EDB-B2BA-912191A724A6
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
2017-07-21 08:46:27 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:00001AB7-B22E-4EDB-B2BA-912191A724A6
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-21 08:46:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-21 08:46:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 279 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-21 08:46:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:27 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-21 08:46:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:28 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-21 08:46:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:29 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-21 08:46:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 282 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'listening 57633'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C36EA720-3E99-469E-993F-ADCEBE140567
,[ThaliCore] Browser.startListening
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:31EB686E-9044-4EEE-A274-31621F2214FC
,2017-07-21 08:46:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-21 08:46:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","generation":0}]'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","generation":0}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9A320958-A40E-4FA4-A2BE-93FF8B9E07DE (syncValue: VCcG1QjTT8ILvwCFrdLWbAxmED31bmDb)'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:31EB686E-9044-4EEE-A274-31621F2214FC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CC9895C0-1863-4433-8EB2-717D7B77F3A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CC9895C0-1863-4433-8EB2-717D7B77F3A7", generation: 0)
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","generation":0}]'
2017-07-21 08:46:30 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","generation":0}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:30 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57637
2017-07-21 08:46:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VCcG1QjTT8ILvwCFrdLWbAxmED31bmDb",,"error":null,"portNumber":57637}'
2017-07-21 08:46:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VCcG1QjTT8ILvwCFrdLWbAxmED31bmDb', error: 'null', listeningPort: '57637''
,2017-07-21 08:46:34 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [16]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:46:34 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:46:34 - DEBUG testUtils: 'Got end'
,ok 283 response body should match testData
,ok 284 must be started
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6
[ThaliCore] Advertiser: session connected Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6
,[ThaliCore] Session.session(_:peer:didChange:) peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6
[ThaliCore] Session.startOutputStream(with:) peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [16, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:16
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] Session.session(_:peer:didChange:) peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6 state: connected -> notConnected
[ThaliCo,re] Advertiser: session notConnected Peer(uuid: "31EB686E-9044-4EEE-A274-31621F2214FC", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.closeStreams() vsID:17
,[ThaliCore] VirtualSocket.handleEventOnInputStream streams are closed
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:true socket error:nil
[ThaliCore] TCPClient.deinit
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:wi,thError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] VirtualSocket.deinit vsID:16 [17]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:true
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6
[ThaliCore] VirtualSocket exited RunLoop ,vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 []
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:2692115E-BDFC-4069-8F1F-BBEBF16BE9A6
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:31EB686E-9044-4EEE-A274-31621F2214FC
,2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-21 08:46:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-21 08:46:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-21 08:46:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:46:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 285 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:57637
,[ThaliCore] Session.disconnect() peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
[ThaliCore] BrowserRelay.deinit
,2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# will fail bad PSK connection between peers
,ok 286 FIX ME, PLEASE!!!
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:45 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-21 08:46:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 288 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-21 08:46:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-21 08:46:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-21 08:46:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 290 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 291 specific error should be returned
,# teardown
,2017-07-21 08:46:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:46:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1D07C8CF-1737-4DDE-9F61-B35248B29157","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:46:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:46:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CC9895C0-1863-4433-8EB2-717D7B77F3A7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 292 error should be null
,ok 293 error should be null
,# setup
,ok 294 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 295 specific error should be returned
,# teardown
,ok 296 error should be null
ok 297 error should be null
,# setup
,ok 298 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'listening 57640'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 299 error should be null
,ok 300 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 301 error should be null
,ok 302 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 303 error should be null
,ok 304 error should be null
,# setup
,ok 305 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'listening 57641'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8C405452-F03E-4007-B29C-ED7065777045
[ThaliCore] Browser.st,artListening
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 308 error should be null
ok 309 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A320958-A40E-4FA4-A2BE-93FF8B9E07DE:0
# teardown
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A320958-A40E-4FA4-A2BE-93FF8B9E07DE", generation: 0)
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","generation":0}]'
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","generation":0}'
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:46:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:46:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9A320958-A40E-4FA4-A2BE-93FF8B9E07DE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 310 error should be null
,ok 311 error should be null
,# setup
,ok 312 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'listening 57642'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7220A1FB-DBF4-4B0F-9C82-B26FA8CB0A7C", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:7220A1FB-DBF4-4B0F-9C82-B26FA8CB0A7C
2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7220A1FB-DBF4-4B0F-9C82-B26FA8CB0A7C", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:7220A1FB-DBF4-4B0F-9C82-B26FA8CB0A7C
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 315 error should be null
ok 316 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:7220A1FB-DBF4-4B0F-9C82-B26FA8CB0A7C
,[ThaliCore] Advertiser.stopAdvertising() peerID:7220A1FB-DBF4-4B0F-9C82-B26FA8CB0A7C
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:46:48 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 317 error should be null
,ok 318 error should be null
,# setup
,ok 319 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'listening 57645'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 322 error should be null
,ok 323 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 324 error should be null
,ok 325 error should be null
,# setup
,ok 326 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-21 08:46:48 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 327 This should not cause wifi to fail
,ok 328 native router should be bad
,# teardown
,ok 329 error should be null
,ok 330 error should be null
,# setup
,ok 331 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-21 08:46:49 - DEBUG thaliMobileNativeWrapper: 'listening 57646'
,ok 332 first call should succeed
,ok 333 first call should succeed
,ok 334 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 335 error should be null
,ok 336 error should be null
,# setup
,ok 337 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-21 08:46:49 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 338 error should be null
,ok 339 error should be null
,# setup
,ok 340 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-21 08:46:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 341 error should be null
ok 342 error should be null
,# setup
,ok 343 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-21 08:46:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ac788b12-34e9-41b1-b2c3-2d0ef1c91bf9","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 344 should be calle,d once
,ok 345 should not have been called more than once
,# teardown
,2017-07-21 08:46:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ac788b12-34e9-41b1-b2c3-2d0ef1c91bf9","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 346 error should be null
ok 347 error should be null
,# setup
,ok 348 ThaliMobile should be stopped
,# can get the network status
,ok 349 network status should have certain non-empty properties
,# teardown
,ok 350 error should be null
ok 351 error should be null
,# setup
,ok 352 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 353 we have not added peer to the cache yet
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6af2db9b-4d09-4a7c-9a7c-d35a05618ecb","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 354 peer should be available
ok 355 cache contains native peer
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6af2db9b-4d09-4a7c-9a7c-d35a05618ecb","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 356 peer should be unavailable
ok 357 peer has been removed from cache
,# teardown
,ok 358 error should be null
ok 359 error should be null
,# setup
,ok 360 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 361 we have not added peer to the cache yet
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5185c3af-d1e3-4d1f-852f-dce8d5abd010","connectionType":"tcp","peerAvailable":true,"generation":0,",newAddressPort":false}'
ok 362 peer should be available
ok 363 cache contains wifi peer
2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"5185c3af-d1e3-4d1f-852f-dce8d5abd010","connectionType":,"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 364 peer should be unavailable
,ok 365 peer has been removed from cache
,# teardown
,ok 366 error should be null
,ok 367 error should be null
,# setup
,ok 368 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ff774b6a-6448-48b0-8c58-814c286d9f8d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 369 first peer is available
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f47aba48-da8a-402c-b45f-1b02ec250e73","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 370 second peer is available
,ok 371 first and second peers are different
,# teardown
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ff774b6a-6448-48b0-8c58-814c286d9f8d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:46:51 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f47aba48-da8a-402c-b45f-1b02ec250e73","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 372 error should be null
,ok 373 error should be null
,# setup
,ok 374 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 375 should not be in cache at start
2017-07-21 08:46:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7f1bcb8e-3636-4d1e-a25e-4643db3b50d2","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 376 peer is available
,# teardown
,2017-07-21 08:46:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7f1bcb8e-3636-4d1e-a25e-4643db3b50d2","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 377 error should be null
ok 378 error should be null
,# setup
,ok 379 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-21 08:46:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 380 error should be null
ok 381 error should be null
,# setup
,ok 382 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-21 08:46:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 383 error should be null
,ok 384 error should be null
,# setup
,ok 385 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"89a910e8-4339-488c-a2f7-d4008a5fa7cf","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
ok 386 peer should be ,available
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"89a910e8-4339-488c-a2f7-d4008a5fa7cf","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 387 peer should be ,available
ok 388 should store correct generation
,# teardown
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"89a910e8-4339-488c-a2f7-d4008a5fa7cf","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 389 error should be null
,ok 390 error should be null
,# setup
,ok 391 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'listening 57647'
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"afe09a46-2676-4998-b9b2-2f539581aab3","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 392 discovered correct peer
,ok 393 got correct generation
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"afe09a46-2676-4998-b9b2-2f539581aab3","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 394 discovered correct peer
,ok 395 got correct generation
,# teardown
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"afe09a46-2676-4998-b9b2-2f539581aab3","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 396 error should be null
,ok 397 error should be null
,# setup
,ok 398 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'listening 57648'
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"724f08a2-5c79-49e5-bf98-39432fd0835a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 399 discovered available peer
,ok 400 peer is available
,# teardown
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"724f08a2-5c79-49e5-bf98-39432fd0835a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 401 error should be null
,ok 402 error should be null
,# setup
,ok 403 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a602d54c-40c4-448c-99b8-d75c7b68a324","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 404 peer should be available
,2017-07-21 08:46:53 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"a602d54c-40c4-448c-99b8-d75c7b68a324","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 405 peer should be unavailable
,ok 406 should be removed from cache
,# teardown
,ok 407 error should be null
,ok 408 error should be null
,# setup
,ok 409 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'listening 57649'
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8caefa67-27d0-4c8b-b00d-ef3fdabea460","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 410 first peer is expected to be available
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9576a968-15ef-4cd9-9ead-a9fd0600f104","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 411 second peer is expected to be available
2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9576a968-15ef-,4cd9-9ead-a9fd0600f104","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 412 peer became unavailable
,ok 413 it was wifi peer
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9576a968-15ef-4cd9-9ead-a9fd0600f104","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 414 we found peer again
,ok 415 it was wifi peer
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9576a968-15ef-4cd9-9ead-a9fd0600f104","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,# teardown
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8caefa67-27d0-4c8b-b00d-ef3fdabea460","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 418 error should be null
,ok 419 error should be null
,# setup
,ok 420 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-21 08:46:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 421 error should be null
,ok 422 error should be null
,# setup
,ok 423 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'listening 57650'
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9ad06e89-4920-4d64-a68b-cfb463c8d5e4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 424 first peer is expected to be available
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0cb58e36-f521-4710-88ee-1963fdb80a64","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 425 second peer is expected to be available
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9ad06e89-4920-4d64-a68b-cfb463c8d5e4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 426 peer became unavailable
,2017-07-21 08:46:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0cb58e36-f521-4710-88ee-1963fdb80a64","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 427 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 428 error should be null
,ok 429 error should be null
,# setup
,ok 430 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-21 08:46:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 431 error should be null
ok 432 error should be null
,# setup
,ok 433 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-21 08:46:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 434 error should be null
ok 435 error should be null
,# setup
,ok 436 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9c423094-cc94-4358-81e0-1ab9184020f2","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 437 peer discovered ,first time does not have new address
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9c423094-cc94-4358-81e0-1ab9184020f2","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 438 address has not been changed
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9c423094-cc94-4358-81e0-1ab9184020f2","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 439 new port handled correctly
,2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9c423094-cc94-4358-81e0-1ab9184020f2","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
ok 440 new host handled, correctly
2017-07-21 08:46:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9c423094-cc94-4358-81e0-1ab9184020f2","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 441 new,AddressPort is null for unavailable peers
,# teardown
,ok 442 error should be null
,ok 443 error should be null
,# setup
,ok 444 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-21 08:46:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 445 error should be null
,ok 446 error should be null
,# setup
,ok 447 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 448 NOT IMPLEMENTED # SKIP
,# teardown
,ok 449 error should be null
,ok 450 error should be null
,# setup
,ok 451 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-21 08:46:56 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 452 error should be null
ok 453 error should be null
,# setup
,ok 454 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 455 should be equal
,# teardown
,ok 456 error should be null
ok 457 error should be null
,# setup
,ok 458 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-21 08:46:57 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 459 error should be null
,ok 460 error should be null
,# setup
,ok 461 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 462 contains expected properties
ok 463 the same hostAddress
ok 464 the same portNumber
,# teardown
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 465 error should be null
,ok 466 error should be null
,# setup
,ok 467 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 468 contains expected properties
,ok 469 the same hostAddress
,ok 470 the same portNumber
,# teardown
,2017-07-21 08:46:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 471 error should be null
,ok 472 error should be null
,# setup
,ok 473 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'listening 57651'
2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2e11e51c-9744-4dfb-9aa2-4d3bd754f81e","connectionType":"tcp","peerAvailab,le":true,"generation":0,"newAddressPort":false}'
,ok 474 Got specific error message
,# teardown
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2e11e51c-9744-4dfb-9aa2-4d3bd754f81e","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 475 error should be null
,ok 476 error should be null
,# setup
,ok 477 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'listening 57652'
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"62929ce1-c933-4fbe-84ce-2484d73c6b5c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:62929ce1-c933-4fbe-84ce-2484d73c6b5c
,ok 478 native wrapper `disconnect` called once
,ok 479 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-21 08:46:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"62929ce1-c933-4fbe-84ce-2484d73c6b5c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-21 08:46:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:46:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:46:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 480 error should be null
,ok 481 error should be null
,# setup
,ok 482 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-21 08:46:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 483 error should be null
,ok 484 error should be null
,# setup
,ok 485 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-21 08:46:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 486 error should be null
,ok 487 error should be null
,# setup
,ok 488 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-21 08:46:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 489 error should be null
ok 490 error should be null
,# setup
,ok 491 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-21 08:46:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 492 error should be null
ok 493 error should be null
,# setup
,ok 494 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-21 08:46:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 495 error should be null
,ok 496 error should be null
,# setup
,ok 497 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-21 08:47:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 498 error should be null
ok 499 error should be null
,# setup
,ok 500 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-21 08:47:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 501 error should be null
ok 502 error should be null
,# setup
,ok 503 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'listening 57653'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:17E283B1-A94E-4C9D-AB67-2877A09F0BDB
,[ThaliCore] Browser.startListening
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d8b82409-555c-4cdb-b7ef-fd1bc21e904e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 504 Peer availabilities has one entry for our connection type
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"32e24512-82f9-4876-a1d2-71bc06a39428","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 505 Peer availabilities has one entry for our connection type
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d8b82409-555c-4cdb-b7ef-fd1bc21e904e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"32e24512-82f9-4876-a1d2-71bc06a39428","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:47:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:47:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 506 No peers
,ok 507 No peers
,ok 508 No peers
,# teardown
,ok 509 error should be null
,ok 510 error should be null
,# setup
,ok 511 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-21 08:47:01 - DEBUG thaliMobileNativeWrapper: 'listening 57654'
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"63c4068a-2557-4f80-aa06-9191f605477d","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 512 1
ok 513 2
,2017-07-21 08:47:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"45b6453c-a01a-4579-99f9-e1e1c2e08f84","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-21 08:47:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"63c4068a-2557-4f80-aa06-9191f605477d","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:47:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"45b6453c-a01a-4579-99f9-e1e1c2e08f84","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-21 08:47:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:47:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-21 08:47:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-21 08:47:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-21 08:47:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 514 error should be null
,ok 515 error should be null
,# setup
,ok 516 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-21 08:47:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 517 error should be null
ok 518 error should be null
,# setup
,ok 519 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'listening 57655'
,ok 520 error should be null
,ok 521 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E271E485-9892-4779-A404-B48D6F6DDB5A
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D7044CB6-EE87-44EA-BE70-5F3B2CDCF0B7
,[ThaliCore] Browser.startListening
,2017-07-21 08:47:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0)
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0)
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:47:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8459AAD8-241C-4AD7-BE87-B4FA7347D935 (syncValue: 0)'
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","generation":0}]'
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","generation":0}'
,2017-07-21 08:47:05 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:47:05 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E271E485-9892-4779-A404-B48D6F6DDB5A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8459AAD8-241C-4AD7-BE87-B4FA7347D935", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57658
2017-07-21 08:47:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":null,"portNumber":57658,}'
,2017-07-21 08:47:08 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for A0E2F326-018E-4AE7-AA79-6AF20D5C5C11 (syncValue: 1)'
2017-07-21 08:47:08 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8459AAD8-241C-4AD7-BE87-B4FA7347D935:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:47:08 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:47:08 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53
[ThaliCore] Advertiser: session connected Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "A0E2F326-018E-4AE7-AA79-6AF20D5C5C11", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57662
,2017-07-21 08:47:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":57662}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A0E2F326-018E-4AE7-AA79-6AF20D5C5C11:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:47:12 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:47:12 - DEBUG testUtils: 'Got end'
,ok 526 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53
,[ThaliCore] Session.session(_:peer:didChange:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53
[ThaliCore] Session.startOutputStream(with:) peer:5D417A4B-30A2-49C8-8399-B9C4A560EA53
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [18, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:184ABA8E-200B-45B1-B43C-D18C7DCD96DA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "184ABA8E-200B-45B1-B43C-D18C7DCD96DA", generation: 0)
2017-07-21 08:47:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}]'
2017-07-21 08:47:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","generation":0}'
,2017-07-21 08:47:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:47:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC
[ThaliCore] Advertiser: session connected Peer(uuid: "E271E485-9892-4779-A404-B48D6F6DDB5A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC
,[ThaliCore] Session.session(_:peer:didChange:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC
[ThaliCore] Session.startOutputStream(with:) peer:A4ED30E9-19CE-4BD6-B254-89C17600C8CC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,1 [18, 19, 20, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:47:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8459AAD8-241C-4AD7-BE87-B4FA7347D935","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21, 08:47:22 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A0E2F326-018E-4AE7-AA79-6AF20D5C5C11","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-21 08:47:22 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"184ABA8E-200B-45B1-B43C-D18C7DCD96DA","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.,stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E271E485-9892-4779-A404-B48D6F6DDB5A
2017-07-21 08:47:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
201,7-07-21 08:47:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
2017-07-21 08:47:22 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-21 08:47:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-21 08:47:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-21 08:47:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 527 error should be null
,ok 528 error should be null
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] VirtualSocket.closeS,treams() vsID:21
# setup
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
,[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [18, 19, 21]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:21
[ThaliCore] VirtualSocket.deinit vsID:21 [18, 19]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:con,nected
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [18]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, ,count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] VirtualSocket.deinit vsID:18 []
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 529 ThaliMobile should be stopped
,# test for data corruption
,2017-07-21 08:47:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 530 error should be null
,ok 531 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 532 getPeerIdentifier
ok 533 getConnectionType
,ok 534 getActionType
,ok 535 getActionState
,ok 536 getPskIdentity
,ok 537 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 538 initial state
ok 539 after start
2017-07-21 08:47:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-21 08:47:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 542 clean kill
ok 543 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 544 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 545 forever agent should have it's own destroy method
,ok 546 agent's destroy should be called
ok 547 agent's destroy should not be called again
ok 548 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 549 Entry counter must be 1
,ok 550 Entry exists
,ok 551 Size must be 1
,ok 552 Entry counter must be 2
,ok 553 Entry exists
,ok 554 Size must be 2
,ok 555 Entry counter must be 1
,ok 556 Entry exists
,ok 557 Size must be 3
,ok 558 Entry counter must be 2
,ok 559 Entry exists
,ok 560 Size must be 4
,ok 561 Entry 1_1 should not be found
,ok 562 Entry 1_1 does not exist
,ok 563 Size must be 3
,ok 564 Entry 1_2 should not be found
,ok 565 Entry 1_2 does not exist
,ok 566 Size must be 2
,ok 567 should be equal
,ok 568 Entry 2_1 should not be found
,ok 569 Entry 2_2 should not be found
,ok 570 Entry 2_1 does not exist
,ok 571 Entry 2_2 does not exist
,ok 572 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 573 Size must be100
,ok 574 Entries between 20 and MAXSIZE + 20 should exist
,ok 575 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 576 Entries between 6 and MAXSIZE + 4 should exist
,ok 577 Size should be MAXSIZE
,ok 578 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 579 WAITING state entry should not be removed
,ok 580 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 581 Size should be MAXSIZE
,ok 582 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 583 Kill should be called once
,ok 584 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 585 is an agent
,ok 586 enqueue is fine
,ok 587 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 588 is an agent
ok 589 first enqueue is fine
ok 590 is an agent
ok 591 second enqueue is fine
ok 592 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
,ok 593 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 594 is an agent
,ok 595 good enqueue
,ok 596 Identity should match
,2017-07-21 08:47:31 - DEBUG testUtils: 'Got response data'
,2017-07-21 08:47:31 - DEBUG testUtils: 'Got end'
,ok 597 Got expected response
,ok 598 Got psk call back
,# teardown
,2017-07-21 08:47:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 599 is an agent
ok 600 enqueue worked
ok 601 is an agent
ok 602 enqueue 2 worked
,ok 603 enqueue is not available when stopped
ok 604 start action is killed
ok 605 killed action is still killed
ok 606 enqueued action when stopped is killed
ok 607 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 608 good start
,ok 609 good enqueue
,ok 610 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 611 null arg
ok 612 wrong arg type
ok 613 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 614 good enqueue
ok 615 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 616 good enqueue
ok 617 2nd good enqueue
ok 618 we are in the pool
ok 619 We are out of the pool
ok 620 Action was killed
ok 621 The original kill was called too
ok 622 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 623 good enqueue
,ok 624 first kill
,ok 625 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 626 1st good enqueue
,ok 627 2nd good enqueue
,ok 628 1st action is in the pool
,ok 629 2nd action is in the pool
,ok 630 1st action is out of the pool
,ok 631 2st action is out of the pool
,ok 632 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-21 08:47:33 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 633 Got right error
,ok 634 Start should not be called
,ok 635 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:47:34 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 636 Got right error
,ok 637 Start should not be called
,ok 638 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 639 Got null
,2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 640 is an agent
2017-07-21 08:47:34 - DEBUG thaliPeerPoolOneAtATime: 'actio,n returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 641 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 642 Got Null
ok 643 Got another null
2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 644 is an agent
2017-07-21 08:47,:35 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 645 is an agent
,2017-07-21 08:47:35 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 646 Action 1 killed at least once
,ok 647 Action 1 went first
,ok 648 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 649 should have gotten null
2017-07-21 08:47:36 ,- DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 650 Should have stopped nicely
2017-07-21 ,08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 651 Still looking for null
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 652 Yup, another null
,ok 653 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 654 Null 1
ok 655 (unnamed assert)
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 656 is an agent
,ok 657 Null 3
ok 658 Replication not yet called
ok 659 Notification 2 not yet called
2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: notificationAction'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,ok 660 is an agent
,ok 661 Notification went first
,ok 662 Notification 2 not called yet
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,ok 663 is an agent
,ok 664 Notification finished
,ok 665 Replication finished
,2017-07-21 08:47:36 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 666 is an agent
ok 667 First does, not throw
2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 668 is an agent
ok 669 Second does not throw
,2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-21 08:47:37 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 first ok
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 672 is an agent
,ok 673 second ok
,ok 674 third ok
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-21 08:47:38 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-21 08:47:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-21 08:47:38 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 675 peerIdentifier should match
,ok 676 generation should match
,ok 677 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 678 good beacon
,ok 679 good preAmble
,ok 680 public keys match!
,ok 681 must return null after successful call
,ok 682 Once start returns the action should be in KILLED state
,# teardown
,2017-07-21 08:47:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-21 08:47:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-21 08:47:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 683 Response should be NETWORK_PROBLEM
,ok 684 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-21 08:47:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 685 Resolution should be BAD_PEER
,ok 686 correct error message
,# teardown
,2017-07-21 08:47:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 687 Call start once
,ok 688 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 689 must return null after successful call.
,# teardown
,2017-07-21 08:47:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 690 Should be Killed
,ok 691 Start after killed
,# teardown
,2017-07-21 08:47:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 692 Should be KILLED
,ok 693 must return null after successful kill
,# teardown
,2017-07-21 08:47:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 694 Should be KILLED
ok 695 must return null after successful kill
,# teardown
,2017-07-21 08:47:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 696 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 697 must return null after successful call
,# teardown
,2017-07-21 08:47:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-21 08:47:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 698 Should be NETWORK_PROBLEM caused closing server socket
,ok 699 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 700 Should be NETWORK_PROBLEM caused closing client socket
ok 701 Should be Could not establish TCP connection
,# teardown
,2017-07-21 08:47:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 702 publicKeysToNotify cannot be null
,ok 703 ecdh for local device cannot be null
,ok 704 milliseconds cannot be less than 0
,ok 705 milliseconds cannot be 0
,ok 706 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 707 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 708 should be equal
,ok 709 should be equal
,ok 710 (unnamed assert)
,ok 711 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 712 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 713 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 714 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 715 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 717 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-21 08:47:54 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 719 should be equal
,ok 720 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 721 right number of calls to address book
,ok 722 good preAmble
,ok 723 good unencryptedKeyId
,ok 724 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 725 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 726 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 727 Matching numbers
,ok 728 We have an entry!
ok 729 keys match
,ok 730 secrets match
,ok 731 We have an entry!
ok 732 keys match
,ok 733 secrets match
,ok 734 We have an entry!
ok 735 keys match
,ok 736 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 737 Streams have same length
,ok 738 matching size
,ok 739 keys match
,ok 740 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 741 should be equal
,ok 742 peerDictionalty contains 2 peers
,ok 743 bluetooth peer's notification has correct connection type
,ok 744 tcp peer's notification has correct connection type
,2017-07-21 08:47:58 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,2017-07-21 08:47:58 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 08:48:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 745 notification peer dictionary contains exactly 1 peer
2017-07-21 08:48:01 - WARN thaliNotificationClient: 'peer is not available'
,ok 746 notification peer dictionary does not contain any peers
2017-07-21 08:48:01 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-21 08:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 747 entry exists
,ok 748 entry is resolved
,# teardown
,2017-07-21 08:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 749 Action should be KILLED
,ok 750 Peer state should be RESOLVED
,# teardown
,2017-07-21 08:48:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 751 hostAddress must match
,ok 752 portNumber must match
,ok 753 suggestedTCPTimeout must match
,ok 754 connectionType must match
,ok 755 peerIDs must match
,# teardown
,2017-07-21 08:48:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 756 Correct error
,# teardown
,2017-07-21 08:48:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 757 hostAddress must match
,ok 758 portNumber must match
,ok 759 suggestedTCPTimeout must match
,ok 760 connectionType must match
,ok 761 peerIds must match
,# teardown
,2017-07-21 08:48:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-21 08:48:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:48:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 763 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:48:05 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 764 action should be resolved with NETWORK_PROBLEM error
,2017-07-21 08:48:06 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 765 action should be resolved with NETWORK_PROBLEM error
ok 766 correct number of requests
ok 767 correct number of failures
ok 768 correct final peer state
,# teardown
,2017-07-21 08:48:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-21 08:48:08 - WARN thaliNotificationClient: 'peer is not available'
2017-07-21 08:48:08 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 769 peerDictionary should become empty
,# teardown
,2017-07-21 08:48:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-21 08:48:09 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 failed with expected error
ok 771 peer state should be RESOLVED
,# teardown
,2017-07-21 08:48:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-21 08:48:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 772 First action failed
,ok 773 second action killed
# teardown
,2017-07-21 08:48:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 774 secrets are equal
,ok 775 Public key matches with the server key
,ok 776 hostAddress must match
,ok 777 portNumber must match
,ok 778 suggestedTCPTimeout must match
,ok 779 connectionType must match
,# teardown
,2017-07-21 08:48:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 780 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 781 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-21 08:48:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 783 All keys need to be available in the cache
,ok 784 All entries should be expired after 1 second
# teardown
,2017-07-21 08:48:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 785 Size of the cache should be 2
,ok 786 Cache doesn't contain dictionary1
,ok 787 Size of the cache should be 1
,ok 788 Cache doesn't contain beaconStreamAndSecretDictionary2
,# teardown
,2017-07-21 08:48:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 789 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 790 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-21 08:48:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 791 StartUpdateAdvertisingAndListening should not be called
,ok 792 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 793 no error
,ok 794 should be 204
,# teardown
,2017-07-21 08:48:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 795 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:48:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 796 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-21 08:48:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 797 no error
,ok 798 should be 200
,ok 799 should be equal
,ok 800 should be equal
,ok 801 (unnamed assert)
,ok 802 no error
,ok 803 should be 204
,# teardown
,2017-07-21 08:48:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 804 error should be null
,ok 805 should be 204
,# teardown
,2017-07-21 08:48:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 806 should be 404
,# teardown
,2017-07-21 08:48:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 807 equal keys
,ok 808 not equal connection type
,ok 809 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-21 08:48:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 811 second cleared dictionary
,2017-07-21 08:48:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 812 First start and on called correctly
,ok 813 First stop and removeListener called correctly
,ok 814 first action kill called
,ok 815 second action kill called
,ok 816 first cleared dictionary
,ok 817 first cleared pool
,ok 818 second cleared dictionary
,ok 819 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 820 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-21 08:48:21 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
,ok 821 listener has been set
,ok 822 peer dictionary has expected number of entries
,ok 823 Dictionary and pool have same action
,ok 824 ads match
,ok 825 PouchDB matches
,ok 826 DB Names match
,ok 827 public keys match
,ok 828 peer dictionary has expected number of entries
,ok 829 Dictionary and pool have same action
,ok 830 ads match
,ok 831 PouchDB matches
,ok 832 DB Names match
,ok 833 public keys match
,2017-07-21 08:48:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 834 start called once
,ok 835 One entry left
,ok 836 Dictionary and pool have same action
,ok 837 Start never called
,ok 838 Kill called once
,ok 839 no entries left
,ok 840 Third action is dead
ok 841 peer dictionary has expected number of entries
,ok 842 Dictionary and pool have same action
ok 843 ads match
ok 844 PouchDB matches
ok 845 DB Names match
,ok 846 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-21 08:48:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-21 08:48:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-21 08:48:22 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-21 08:48:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 847 right error
,# teardown
,2017-07-21 08:48:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 848 right error
,# teardown
,2017-07-21 08:48:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-21 08:48:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-21 08:48:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-21 08:48:24 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-21 08:48:24 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 850 Got error as expected
,# teardown
,2017-07-21 08:48:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-21 08:48:25 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-21 08:48:25 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 851 Got error as expected
,# teardown
,2017-07-21 08:48:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-21 08:48:28 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:28 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:48:31 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-21 08:48:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-21 08:48:33 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:33 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:48:36 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 854 should be equal
ok 855 All tests passed!
,# teardown
,2017-07-21 08:48:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-21 08:48:36 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-21 08:48:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:48:38 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 856 action should be killed
ok 857 Error should be timed out
,ok 858 No doc found
,# teardown
,2017-07-21 08:48:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-21 08:48:40 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-21 08:48:41 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 859 should be equal
,2017-07-21 08:48:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:48:42 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
,ok 860 action should be killed
ok 861 Error should be timed out
,# teardown
,2017-07-21 08:48:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 862 socket hung up
,# teardown
,2017-07-21 08:48:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 863 same getPeerAdvertisesDataForUs
ok 864 Same pouchdB
ok 865 same localDbName
ok 866 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-21 08:48:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-21 08:48:45 - DEBUG thaliMobileNativeWrapper: 'listening 57791'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E52D12A4-E7C0-400A-91E5-2362DDE37040
[ThaliCore] Browser.startListening
2017-07-21 08:48:45 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:71D9EF6F-6E7A-4A39-8A89-C097EA09540E
,2017-07-21 08:48:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
2017-07-21 08:48:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"B4AFDE44-9DFC-487A-ACDF-78DA33AF1092","generation":0}]'
2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"B4AFDE44-9DFC-487A-ACDF-78DA33AF1092","generation":0}'
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"B4AFDE44-9DFC-487A-ACDF-78DA33AF1092","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-21 08:48:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"B4AFDE44-9DFC-487A-ACDF-78DA33AF1092","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Issuing multi,Connect for B4AFDE44-9DFC-487A-ACDF-78DA33AF1092 (syncValue: 2)'
2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B4AFDE44-9DFC-487A,-ACDF-78DA33AF1092", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:,notConnected:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:52D46020-2085-46B8-B61C-0464BC17069B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
2017-07-21 08:48:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"52D46020-2085-46B8-B61C-0464BC17069B","generation":0}]'
2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"52D46020-2085-46B8-B61C-0464BC17069B","generation":0}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.session(_:peer:didChange:) peer:D300F900-F958-490F-97A7-9933875788EF state: notConnected -> connecting
[ThaliCore] Advertiser: session connected Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,2017-07-21 08:48:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"52D46020-2085-46B8-B61C-0464BC17069B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-21 08:48:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"52D46020-2085-46B8-B61C-0464BC17069B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71D9EF6F-6E7A-4A39-8A89-C097EA09540E:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Advertiser: session connected Peer(uuid: "71D9EF6F-6E7A-4A39-8A89-C097EA09540E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] Session.session(_:peer:didChange:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "B4AFDE44-9DFC-487A-ACDF-78DA33AF1092", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57794
,2017-07-21 08:48:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":57794}'
,2017-07-21 08:48:49 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 52D46020-2085-46B8-B61C-0464BC17069B (syncValue: 3)'
,2017-07-21 08:48:49 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:D300F900-F958-490F-97A7-9933875788EF state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [23]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 []
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] TCPClient: didConnectToHost, active connection,s count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [24, 25]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:50 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [24, 25, 26]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [24, 25, 26, 27]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [24, 25, 26, 27, 28]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:29 [24, 25, 26, 27, 28, 29]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [24, 25, 26, 27, 28, 29, 30]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [24, 25, 26, 27, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [24, 25, 26, 27, 28, 29, 30, 31, 32]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [24, 25, 26, 27, 28, 29, 30, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
,[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:31
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:31 [24, 25, 26, 27, 28, 29, 30, 32, 33]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D300F900-F958-490F-97A7-9933875788EF
[ThaliCore] Session.startOutputStream(with:) peer:D300F900-F958-490F-97A7-9933875788EF
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [24, 25, 26, 27, 28, 29, 30, 32, 33, 34]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:34 [24, 25, 26, 27, 28, 29, 30, 32, 33]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [24, 25, 26, 27, 28, 29, 30, 32, 33, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [24, 25, 26, 27, 28, 29, 30, 32, 33, 35, 36]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-21 08:48:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
,[ThaliCore] VirtualSocket.deinit vsID:35 [24, 25, 26, 27, 28, 29, 30, 32, 33, 36]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [24, 25, 26, 27, 28, 29, 30, 32, 33]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [24, 25, 26, 27, 28, 29, 30, 32, 33, 37]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [24, 25, 26, 27, 28, 29, 30, 32, 33, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [24, 25, 26, 27, 28, 29, 30, 32, 33, 37, 38, 39]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "52D46020-2085-46B8-B61C-0464BC17069B", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:57814
,2017-07-21 08:48:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":57814}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [24, 25, 26, 27, 28, 29, 30, 32, 33, 37, 38, 39, 40]
[ThaliCore] BrowserRelay.didOp,enVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:40 [24, 25, 26, 27, 28, 29, 30, 32, 33, 37, 38, 39]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [24, 25, 26, 27, 28, 29, 30, 32, 33, 37, 38, 39, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [24, 25, 26, 27, 28, 29, 30, 32, 33, 37, 38, 39, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B4AFDE44-9DFC-487A-ACDF-78DA33AF1092:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [24, 25, 26, 27, 28, 29, 30, 32, 33, 37, 38, 39, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-21 08:48:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:28
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NS,LocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] VirtualSocket exited RunLoop vsID:25
,[ThaliCore] VirtualSocket.deinit vsID:25 [24, 26, 27, 28, 29, 30, 32, 33, 37, 38, 39, 41, 42, 43]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:27
,[ThaliCore] VirtualSocket.deinit vsID:27 [24, 26, 28, 29, 30, 32, 33, 37, 38, 39, 41, 42, 43]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:28 [24, 26, 29, 30, 32, 33, 37, 38, 39, 41, 42, 43]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.deinit vsID:32 [24, 26, 29, 30, 33, 37, 38, 39, 41, 42, 43]
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
[ThaliCore] VirtualSocket.deinit vsID:43 [24, 26, 29, 30, 33, 37, 38, 39, 41, 42]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [26, 29, 30, 33, 37, 38, 39, 41, 42]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDi,sconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCor,e] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [29, 30, 33, 37, 38, 39, 41, 42]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [29, 33, 37, 38, 39, 41, 42]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:33 [29, 37, 38, 39, 41, 42]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [29, 37, 38, 39, 41, 42, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] Session.startOutputStream(with:) peer:975DE0CF-EB9D-4122-B336-EF44AAA7FFB9
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,5 [29, 37, 38, 39, 41, 42, 44, 45]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [29, 37, 38, 39, 41, 42, 44, 45, 46]
[ThaliCore] BrowserRelay.didOpenVirtualSocketS,treamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:52D46020-2085-46B8-B61C-0464BC17069B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [29, 37, 38, 39, 41, 42, 44, 45, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] VirtualSocket.deinit vsID:46 [29, 37, 38, 39, 41, 42, 44, 45, 47]
,2017-07-21 08:48:54 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:37
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
,[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] VirtualSocket.deinit vsID:37 [29, 38, 39, 41, 42, 44, 45, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:39
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [29, 38, 39, 41, 42, 44, 47]
[ThaliCore] VirtualSocket exited RunLoop vsID:38
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] VirtualSocket.deinit vsID:38 [29, 39, 41, 42, 44, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay,.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [29, 41, 42, 44, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-21 08:48:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-21 08:48:56 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:42
[ThaliCore] TCPListener.socketDidDi,s,connect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler ,state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:41
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] VirtualSocket.deinit vsID:41 [29, 42, 44, 47]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.deinit vsID:42 [29, 44, 47]
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] VirtualSocket.deinit vsID:44 [29, 47]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [29]
,2017-07-21 08:51:45 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-21 08:51:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:51:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:51:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:51:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:52:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:52:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:53:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:53:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:54:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:54:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:55:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:55:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:56:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:56:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:57:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:57:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-21 08:58:45 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-21 08:58:45 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make su,re we time out'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error w,hen server goes'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-21 08:58:45 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-21 08:58:45 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-21 08:58:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:58:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 867 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-21 08:58:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:58:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 08:59:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 08:59:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:00:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:00:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:01:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4,A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-21 09:01:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A6,7-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-21 09:01:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/39B32AC8-67D6-4A67-B0FE-9ABCB747906F/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
