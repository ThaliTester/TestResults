#### Test 11335185130e646f_iOS_Iphone6sPlus-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/3FA9B0A0-ECEC-40B1-94FB-5E595F36307D/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'
,Executing commands in '/tmp/3FA9B0A0-ECEC-40B1-94FB-5E595F36307D/fruitstrap-lldb-prep-cmds-f70cda60583ea0f895d05ea355cd125983c27594'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185130e646f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53114"
,(lldb)     command script import "/tmp/3FA9B0A0-ECEC-40B1-94FB-5E595F36307D/fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.py"
,(lldb)     command script add -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_f70cda60583ea0f895d05ea355cd125983c27594.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-28 10:20:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:20:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:20:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:20:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:20:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:20:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:20:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1517AF55-D487-4B62-9925-D8FE5F18893E", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:1517AF55-D487-4B62-9925-D8FE5F18893E
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:40227FB4-C9B7-4C6E-9D71-8EA7947F6D62
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:259DB433-AE8E-4131-8926-8E19C4826777
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "0D6C453A-6B9E-4A37-A0C5-071AC5B25F74", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:0D6C453A-6B9E-4A37-A0C5-071AC5B25F74
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0D6C453A-6B9E-4A37-A0C5-071AC5B25F74:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0D6C453A-6B9E-4A37-A0C5-071AC5B25F74", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTes,ts finished
All tests finished
All tests finished
,2017-07-28 10:20:58 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.57769387960434
2017-07-28 10:20:58 - DEBUG UnitTest_app: 'My device name is: 'Apple-Iphone6sPlus-1''
2017-07-28 10:20:58 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0D6C453A-6B9E-4A37-A0C5-071AC5B25F74:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0D6C453A-6B9E-4A37-A0C5-071AC5B25F74", generation: 0)
,2017-07-28 10:20:59 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-28 10:20:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-28 10:21:00 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-28 10:21:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-28 10:21:01 - DEBUG UnitTest_app: 'Unit Test app is loaded'
appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-28 10:21:01 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-28 10:21:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:21:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:21:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:21:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:21:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:21:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:21:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:21:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:21:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:21:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:21:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:21:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:21:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:21:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:21:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:22:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:22:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:22:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:22:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:22:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:22:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:22:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:22:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:22:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:22:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:22:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:22:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4,EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:23:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:23:45 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-28 10:23:45 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-28 10:23:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-28 10:23:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-28 10:23:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-28 10:23:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-28 10:23:55 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-28 10:23:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-28 10:23:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-28 10:23:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,ok 32 fourth
,ok 33 second
,ok 34 secondPromise - in then
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
,2017-07-28 10:24:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-28 10:24:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-28 10:24:13 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,2017-07-28 10:24:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:24:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-28 10:24:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:28 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:24:28 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:24:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:20E0E584-06C4-4FCF-B603-5C55771AF68C
[ThaliCore] Browser.startListening
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:24:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvert,isements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:24:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:24:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BBF48EDB-854B-4F2F-A92F-7080887D13A9
[ThaliCore] Browser.startListening
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28, 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call stopListeningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:30 - ,DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call sto,pListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:24:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5DB8CEBA-EDE4-4F17-9620-BE464C2371E6", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5DB8CEBA-EDE4-4F17-9620-BE464C2371E6
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5DB8CEBA-EDE4-4F17-9620-BE464C2371E6
2017-07-28 10:24:31 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call ,s,topAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:24:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-28 10:24:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4149F31A-6633-4CA0-A729-7F2ED176D963", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:4149F31A-6633-4CA0-A729-7F2ED176D963
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4149F31A-6633-4CA0-A729-7F2ED176D963", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:4149F31A-6633-4CA0-A729-7F2ED176D963
2017-07-28 1,0:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:2,4:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4149F31A-6633-4CA0-A729-7F2ED176D963
[ThaliCore] Advertiser.s,topAdvertising() peerID:4149F31A-6633-4CA0-A729-7F2ED176D963
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:32 - DEBUG thaliMo,bileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:24:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:24:33 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:24:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64
,2017-07-28 10:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:354E0E81-3839-443D-AE21-A9330D6E7,409
[ThaliCore] Browser.startListening
2017-07-28 10:24:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:24:37 - INFO thaliMobile: 'Received state ({"discoveryA,ctive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:37 - INFO thaliMobil,e: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DF6EC92-4C39-48D4-90E9-D0752BF3BD64:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DF6EC92-4C39-48D4-90E9-D0752BF3BD64", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 ,10:24:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2DF6EC92-4C39-48D4-90E9-D,0752BF3BD64
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07,-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A
,2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:643EA949-813F-4976-9EB7-0C17CF196E13
[ThaliCore] Browser.startListening
2017-07-28 10:24:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:24:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-28 10:24:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
2017-07-28 10:24:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2C90D592-5A1A-4AB3-9831-94152F0137BD","generation":0}'
2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2C90D592-5A1A-4AB3-9831-94152F0137BD, (syncValue: dIL5dYpZLD8IpUHPZKmqQDHsgSJp3AQD)'
2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0,137BD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found p,eer:4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2C90D592-5A1A-4AB3-983,1-94152F0137BD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24","generation":0}'
2017-07-28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,28 10:24:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4428E5F1-DF44-4A45-AACC-1ED6AAD9FC24", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
2017-07-28 10:24:42 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FDF967AF-AC1F-48BB-BDA5-DC0E81797566","generation":0}'
2017-07-28 10:24:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:24:42 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8B8E5E40-BA6B-4AFA-A8E7-23B642839774:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8B8E5E40-BA6B-4AFA-A8E7-23B642839774", generation: 0)
2017-07-28 10:24:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"8B8E5E40-BA6B-4AFA-A8E7-23B642839774","generation":0}'
2017-07-28 10:24:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:24:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2C,90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2C90D592-5A1A-4AB3-9831-94152F0137BD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:24:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dIL5dYpZLD8IpUHPZKmqQDHsgSJp3AQD","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dIL5dYpZLD8IpUHPZKmqQDHsgSJp3AQD', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:24:44 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FDF967AF-AC1F-48BB-BDA5-DC0E81797566 (syncValue: sldlHgNSR4V4gI5tB9KQB5W,XZ8oEik0m)'
2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E8,1797566:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8120360A-B668-4F82-9C62-C4287F089F29
[ThaliCore] Advertiser: session connected Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8120360A-B668-4F82-9C62-C4287F089F29 state: notConnected -> connec,ting
2017-07-28 10:24:44 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2C90D592-5A1A-4AB3-9831-94152F0137BD:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F8DA3440-6F56-4ADA-8858-5EA283505900
[ThaliCore] Advertiser: session connected Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:F8DA3440-6F56-4ADA-8858-5EA283505900 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8120360A-B668-4F82-9C62-C4287F089F29
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] Session.session(_:peer:didChange:) peer:8120360A-B668-4F82-9C62-C4287F089F29 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62960
,2017-07-28 10:24:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"sldlHgNSR4V4gI5tB9KQB5WXZ8oEik0m","error":null,"portNumber":62960}'
,2017-07-28 10:24:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'sldlHgNSR4V4gI5tB9KQB5WXZ8oEik0m', error: 'null', listeningPort: '62960''
,2017-07-28 10:24:47 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F8DA3440-6F56-4ADA-8858-5EA283505900
,[ThaliCore] Session.session(_:peer:didChange:) peer:F8DA3440-6F56-4ADA-8858-5EA283505900 state: connecting -> connected
,2017-07-28 10:24:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:24:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:24:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:24:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62960
[ThaliCore] Session.disconnect,() peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:F8DA3440-6F56-4ADA-8858-5EA283505900 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:F8DA3440-6F56-4ADA-8858-5EA283505900
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8120360A-B668-4F82-9C62-C4287F089F29 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "BF44BF5E-C20B-44D2-BDD7-247D52CA9B5A", generation: 0)
,[ThaliCore] Session.deinit peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:24:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:24:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:F8DA3440-6F56-4ADA-8858-5EA283505900
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7
,2017-07-28 10:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:24:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 86 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:83352589-F114-40FD-A8E8-A577BA592395
,[ThaliCore] Browser.startListening
,2017-07-28 10:24:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:24:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-28 10:24:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
,2017-07-28 10:24:51 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FDF967AF-AC1F-48BB-BDA5-DC0E81797566","generation":0}'
,2017-07-28 10:24:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FDF967AF-AC1F-48BB-BDA5-DC0E81797566 (syncValue: a5rOUNWtAYgyjpozNghll7Omr2ppyTOs)'
,2017-07-28 10:24:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
2017-07-28 10:24:51 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F84CD8E8-8996-4FBF-892D-97FE4B025995","generation":0}'
2017-07-28 10:24:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:24:51 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
2017-07-28 10:24:52 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA","generation":0}'
2017-07-28 10:24:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:24:52 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:24:52 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:686215DE-C39C-468F-A1DE-C360CB2CBF2F
[ThaliCore] Advertiser: session connected Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:686215DE-C39C-468F-A1DE-C360CB2CBF2F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,F967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:686215DE-C39C-468F-A1DE-C360CB2CBF2F
,[ThaliCore] Session.session(_:peer:didChange:) peer:686215DE-C39C-468F-A1DE-C360CB2CBF2F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:686215DE-C39C-468F-A1DE-C360CB2CBF2F
[ThaliCore] Session.startOutputStream(with:) peer:686215DE-C39C-468F-A1DE-C360CB2CBF2F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-28 10:24:54 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-28 10:24:54 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-28 10:24:54 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-28 10:24:54 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:1
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client discon,nected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,F967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,F967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,DF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4A04F713-3F43-4524-81DB-048DA457F037
[ThaliCore] Advertiser: session connected Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4A04F713-3F43-4524-81DB-048DA457F037 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FD,F967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:FDF967AF,-AC1F-48BB-BDA5-DC0E81797566 error: max retries exceeded
[ThaliCore] Session.deinit peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserRelay.deinit
2017-07-28 10:25:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"a5,rOUNWtAYgyjpozNghll7Omr2ppyTOs","error":"Connection could not be established","portNumber":null}'
2017-07-28 10:25:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'a5rOUNWtAYgyjpozNghll7Omr2ppyTOs', error: 'Connection could n,o,t be established', listeningPort: '%s''
,2017-07-28 10:25:02 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-28 10:25:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F84CD8E8-8996-4FBF-892D-97FE4B025995 (syncValue: SjeUf1g,3hEIHqBXSRGTyOWYPTYowlMiZ)'
2017-07-28 10:25:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F84CD8E8-8996,-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:25:02 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-28 10:25:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FDF967AF-AC1F-48BB-BDA5-DC0E81797566:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FDF967AF-AC1F-48BB-BDA5-DC0E81797566", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4A04F713-3F43-4524-81DB-048DA457F037
,[ThaliCore] Session.session(_:peer:didChange:) peer:4A04F713-3F43-4524-81DB-048DA457F037 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4A04F713-3F43-4524-81DB-048DA457F037
[ThaliCore] Session.startOutputStream(with:) peer:4A04F713-3F43-4524-81DB-048DA457F037
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-28 10:25:03 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-07-28 10:25:03 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-07-28 10:25:03 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
,2017-07-28 10:25:03 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62975
2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SjeUf1g3hEIHqBXSRGTyOWYPTYowlMiZ",,"error":null,"portNumber":62975}'
2017-07-28 10:25:04 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SjeUf1g3hEIHqBXSRGTyOWYPTYowlMiZ', error: 'null', listeningPort: '62975''
,Connecting to the localhost:62975
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
Connected to the localhost:62975
2017-07-28 10:25:04 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-28 10:25:04 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pee,r})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams,() vsID:3
# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [2]
,2017-07-28 10:25:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:25:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.disconnect peer:F84CD8E8-8996-4FBF-892D-97FE4B025995
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:62975
[ThaliCore] Session.disconnect,() peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] Browse,rRelay.deinit
2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-,2,8 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:25:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:25:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:686215DE-C39C-468F-A1DE-C360CB2CBF2F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B3D93E1A-81F0-4F0E-9077-1EB4EBA3F8F7", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4A04F713-3F43-4524-81DB-048DA457F037
,[ThaliCore] Session.deinit peer:4A04F713-3F43-4524-81DB-048DA457F037
[ThaliCore] AdvertiserRelay.deinit
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D6DE573A-0E5A-4BD7-B7BC-01111EFB454A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D6DE573A-0E5A-4BD7-B7BC-01111EFB454A
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:92801593-27A4-4FE2-8CEA-0ECE5BDC,62E1
[ThaliCore] Browser.startListening
2017-07-28 10:25:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:25:06 - INFO thaliMobile: 'Received state ({"discover,y,Active":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:25:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'W,e got a peer {"peerAvailable":true,"peerIdentifier":"AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA","generation":0}'
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA (syncValue: GHxu1GCUEfXicrqaPxst7j8EXWDLZeLm)'
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F84CD8E8-8996-4FBF-892D-97FE4B025995","generation":0}'
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:06 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C4A28E9-2035-47E8-A153-BA2B2523267F","generation":0}'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"39056CDE-F8B9-4D96-B071-8452DE2C822B","generation":0}'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D6DE573A-0E5A-4BD7-B7BC-01111EFB454A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D6DE573A-0E5A-4BD7-B7BC-01111EFB454A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AE,58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,E58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AE,58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,E58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F84CD8E8-8996-4FBF-892D-97FE4B025995:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F84CD8E8-8996-4FBF-892D-97FE4B025995", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AE,58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,E58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:AE,58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:AE58163C,-9F4D-4F5D-AAD7-97137B9ADAEA error: max retries exceeded
2017-07-28 10:25:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GHxu1GCUEfXicrqaPxst7j8EXWDLZeLm","error":"Connection could not be established","portNumber":null}'
2017-0,7-28 10:25:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'GHxu1GCUEfXicrqaPxst7j8EXWDLZeLm', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-28 10:25:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-28 10:25:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4C4A28E9-2035-47E8-A153-BA2B2523267F (syncValue: V6mgbgU,FU2YGyAeTrjpYwI4T08KtUnyw)'
2017-07-28 10:25:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4C4A28E9-2035,-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:25:16 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-28 10:25:17 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:AE58163C-9F4D-4F5D-AAD7-97137B9ADAEA:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:62983
2017-07-28 10:25:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"V6mgbgUFU2YGyAeTrjpYwI4T08KtUnyw",,"error":null,"portNumber":62983}'
2017-07-28 10:25:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'V6mgbgUFU2YGyAeTrjpYwI4T08KtUnyw', error: 'null', listeningPort: '62983''
,Connecting to the localhost:62983
Connecting to the localhost:62983
Connecting to the localhost:62983
Connected to the localhost:62983
Connected to the localhost:62983
Connected to the localhost:62983
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 4]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-28 10:25:19 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 4, 5]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 4, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 94 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [2, 5, 6]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 6]
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] VirtualSocket.deinit vsID:6 [2]
,ok 96 got the same data back
,# teardown
,2017-07-28 10:25:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D6DE573A-0E5A-4BD7-B7BC-01111EFB454A
2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:25:30 - ,INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:4C4A28E9-2035-47E8-A153-BA2B2523267F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopLi,steningForConnectionsAndDisconnectClients() port:62983
[ThaliCore] Session.disconnect() peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:25:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:25:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:7EB6E114-08CB-40BC-BC8E-AF9C5927C203
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E27A78DD-DA18-4C07-8B3B-0880CF420AAE
[ThaliCore] Browser.startListening
2017-07-28 10:25:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:25:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-28 10:25:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"39056CDE-F8B9-4D96-B071-8452DE2C822B","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4C4A28E9-2035-47E8,-A153-BA2B2523267F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 39056CDE-F8B9-4D96-B071-8452DE2C822B (syncValue: U3Bw73deDi1YCnkApaGjYoDOCyUnlQvi)'
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4C4A28E9-2035-47E8-A153-BA2B2523267F","generation":0}'
,2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
2017-07-28 10:25:32 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2923606D-3F00-4705-8BE9-987546819CD0","generation":0}'
2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:32 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8817D8DE-3A96-471E-BCE8-28B15E159AEF:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8817D8DE-3A96-471E-BCE8-28B15E159AEF", generation: 0)
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8817D8DE-3A96-471E-BCE8-28B15E159AEF","generation":0}'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:25:32 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7EB6E114-08CB-40BC-BC8E-AF9C5927C203:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7EB6E114-08CB-40BC-BC8E-AF9C5927C203", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,9056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:39,056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:39056CDE,-F8B9-4D96-B071-8452DE2C822B error: max retries exceeded
2017-07-28 10:25:42 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"U3Bw73deDi1YCnkApaGjYoDOCyUnlQvi","error":"Connection could not be established","portNumber":null}'
2017-0,7-28 10:25:42 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'U3Bw73deDi1YCnkApaGjYoDOCyUnlQvi', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-28 10:25:42 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-28 10:25:42 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4C4A28E9-2035-47E8-A153-BA2B2523267F (syncValue: hxHTTtt,F5nPDybKlQGY56YCQahiKcyLq)'
2017-07-28 10:25:42 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4C4A28E9-2035,-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:25:42 - DEBUG thaliMobileNativeTestUtils: 'Already running tes,t,!'
2017-07-28 10:25:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:42 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4C,4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:4C,4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4,C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4C4A28E9-2035-47E8-A153-BA2B2523267F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:25:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hxHTTttF5nPDybKlQGY56YCQahiKcyLq","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:25:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'hxHTTttF5nPDybKlQGY56YCQahiKcyLq', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:25:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:25:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2923606D-3F00-4705-8BE9-987546819CD0 (syncValue: dNCnwmAQCB7gzPwLY5GlZM3,CWAWJdLa5)'
2017-07-28 10:25:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2923606D-3F00-4705-8BE9-98754,6819CD0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:25:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 ,1,0:25:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:4C4A28E9-2035-47E8-A153-BA2B2523267F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63007
2017-07-28 10:25:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dNCnwmAQCB7gzPwLY5GlZM3CWAWJdLa5",,"error":null,"portNumber":63007}'
2017-07-28 10:25:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dNCnwmAQCB7gzPwLY5GlZM3CWAWJdLa5', error: 'null', listeningPort: '63007''
,Connecting to the localhost:63007
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 7]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:63007
2017-07-28 10:25:50 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-28 10:25:50 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:39056CDE-F8B9-4D96-B071-8452DE2C822B:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "39056CDE-F8B9-4D96-B071-8452DE2C822B", generation: 0)
,2017-07-28 10:25:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:7EB6E114-08CB-40BC-BC8E-AF9C5927C203
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:25:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:2923606D-3F00-4705-8BE9-987546819CD0
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63007
[ThaliCore] Session.disconnect,() peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2923606D-3F00-4705-8BE9-987546819CD0:0
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:25:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:25:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB
,2017-07-28 10:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:25:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 100 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6F8CB1E9-0556-4BD5-AFFE-3C9FA640F5B9
[ThaliCore] Browser.startListening
,2017-07-28 10:25:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:25:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-28 10:25:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
2017-07-28 10:25:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"2923606D-3F00-4705-8BE9-987546819CD0","generation":0}'
2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2923606D-3F00-4705-8BE9-987546819CD0, (syncValue: reyDz2lRCMhGwQDaxDFTbBZQ4rFYhrqa)'
2017-07-28 10:25:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2923606D-3F00-4705-8BE9-9875468,19CD0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:,) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2DEF4005-6540-42F4-B0CD-F8B75F1A30AB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
2017-07-28 10:25:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61F798BB-B8AE-4376-B306-D7BF1030062F","generation":0}'
2017-07-28 10:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:54 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
2017-07-28 10:25:54 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2","generation":0}'
2017-07-28 10:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:25:54 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:25:54 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:29,23606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,923606D-3F00-4705-8BE9-987546819CD0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:29,23606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,923606D-3F00-4705-8BE9-987546819CD0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:29,23606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,923606D-3F00-4705-8BE9-987546819CD0", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8DCA9EAC-1029-4927-ABDA-5384845F716B
[ThaliCore] Advertiser: session connected Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8DCA9EAC-1029-4927-ABDA-5384845F716B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8DCA9EAC-1029-4927-ABDA-5384845F716B
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DCA9EAC-1029-4927-ABDA-5384845F716B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8DCA9EAC-1029-4927-ABDA-5384845F716B
[ThaliCore] Session.startOutputStream(with:) peer:8DCA9EAC-1029-4927-ABDA-5384845F716B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-28 10:26:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:2923606D-3F00-4705-8BE9-987546819CD0:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:29,23606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:2923606D,-3F00-4705-8BE9-987546819CD0 error: max retries exceeded
2017-07-28 10:26:03 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"reyDz2lRCMhGwQDaxDFTbBZQ4rFYhrqa","error":"Connection could not be established","portNumber":null}'
2017-0,7-28 10:26:03 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'reyDz2lRCMhGwQDaxDFTbBZQ4rFYhrqa', error: 'Connection could not be established', listeningPort: '%s''
2017-07-28 10:26:03 - ERROR thaliMobileNativeTestUtils: 'Fatal ,c,onnect error: 'Connection could not be established''
,2017-07-28 10:26:03 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 61F798BB-B8AE-4376-B306-D7BF1030062F (syncValue: NxlqwoWN4MerKVexBWpVjbf4O1p6pz9J)'
,2017-07-28 10:26:03 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:26:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-28 10:26:03 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:26:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:26:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:04 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Session.session(_:peer:didChange:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0 state: notConnected -> connecting
,2017-07-28 10:26:04 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:06 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63025
2017-07-28 10:26:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NxlqwoWN4MerKVexBWpVjbf4O1p6pz9J",,"error":null,"portNumber":63025}'
2017-07-28 10:26:06 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NxlqwoWN4MerKVexBWpVjbf4O1p6pz9J', error: 'null', listeningPort: '63025''
,Connecting to the localhost:63025
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
Connected to the localhost:63025
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 7, 8, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-28, 10:26:06 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (71 bytes):'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:9 [2, 7, 8]
,ok 102 got the same data back
,# teardown
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:07 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2923606D-3F00-4705-8BE9-987546819CD0:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2923606D-3F00-4705-8BE9-987546819CD0", generation: 0)
,2017-07-28 10:26:08 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:09 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:10 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:10 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:10 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:10 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:10 - DEBUG testThaliMobileNative: 'Server received (931 bytes):'
,2017-07-28 10:26:10 - DEBUG testThaliMobileNative: 'Server received all data: uKvUx22GG8YTzulKayxGuEZ6fKY9S4zp6cg1TCyEZc7zoyQ3BVcVf7fl48Nt1WOdKxpspaQPt4MSKJKhxtv7aWAK88RmYJ5FHeeneNtvKrYgaDwjVFf9sWoW2t4u7fFsBMYFYcBQtLOm0FdSVmLYpOdOBf1vM7aTeTT7wIerLg0szgFwli,lzIEcZAt8ppbB5qsihtQuX9EaIzGa4hjh9jkjAlPavNgdmbSlUhoMO8qSUxPv7WljKODHWFHgG3QnmHCQZVCkPLzn6O3fcznAsyoBqncSlbMOWDO5pcbUyW2lqpp82azXMayDwOmzLVwT7P3sewqr2qyAJYVOPSzrkt8hKzewyp3FYqbHZWYLsmT6t5nhWZc7fXcMQZm771KjDnLeNzIy19UFU0jGTR6TAVB7ePz8jWMNX2Kws6vF7dLhrUtWxnI,5ByGiGoBMEqlkKHdqFLeLbAAVuvqdUluZulZn3GVDTJMizT86VKUyLl8fzEh9AnsOcFjPyAY3tEnzg5Ey6Jmoq9qBa65XoUR2TEYzcvXY8l4T3iGRH6tOjZVGdiER8NfaZE841VIxiPrlnx2RKVrIJHVdgK3THpEpe8TV34CuzOyLyEzD6XwzbCAaRWXi3DZR28HvsQImfbC9R714wRglfCna2T9xQ4ilVVifDCUp6uT93yYkYHz1TKx0LqfGy9y,syXgFQG2rLfC1W0H9137llgZ8lxa3HJtA1OLLvURXPAhkFZlCsCar0J7K6o86EcBtTxK2bE31jFRkE6l3TV8fLLLO7stiTLquMbCHm5lKLQDrrkzW9jzJlNv87oT3Ox5DzotW0dzjtKpBLVARIGUwYqcmRHFBCbvEnwAbNx8gdr9uMZi2wkkOzFFO4Xmg7B7QvbkuN9sjGVF9UL04JQvQv2sNKb5TnOJbpe2pwOpFv1hFYm8QY635uUlL8DKPKn,B,xeDMhOorJSLDtok4PerZlFK2KmZ31kPDInV4IgoQIdle3CC4PKOQzMqlDjBG3cg6FL3VKXrjD2urQ7TlCBMuP6YsNCQHTsjhclLudi7HorqBlmgh7teMI0D8CE64bruQjZjCpFYnV8UGbyPoxGKpoPUMdX1bGuwOEh0hlPGXU2TqOf40CeyjFdR6dulQhc2Tv0K4yaVaHKW5KaKAS1BdY3AUTr5lPvDyOQaxiwr7qiGPWpSDzK6vQQXcMyIdeMy5,zlvvXbU0pMlwfIWlvOWR5YUebxaZmfICUIJZdERN1VWtSG0q73g4d4rSKUNZRafYFUdWNQcKNPsivZCdsEJpqL8OE0IMQaxjzRJ10BrBWgIGPUBb0FvLeXmVP68Ccv7H6EpDB4HyCGnLtrJBnTK1YVtxomXZSQ9by9TnKcOLgoQVE7NRQcvFX5u35Vz2WtAZXLas66jA84noO0yBqGgmGaRLQ3dbbNEvb3H0gtiPSn9rE30RVP43aGORSpfhc4Sq,996Y093es7JaaSlEyftFq2npunoq8ltEAJgNGtX9u0QPv891KM2nenRp4TOwFjw979KPbIvUAo4ELD0ksOmj3wXYWAu1BUdUMBYIf72inWkz5lVb0uqpKp5b8XFvGCZ1CtrhLZC68UipFRRjzkWTcUrMqhCN01v5n1yg8rsxmnaGszo1Hs2AAAsCbgLuuts0YCLvewQwY4ZsEaybngyLXFzQ4aQp5oPTolgpukYDiwV9kDhhP7afmIoaPiRMaduB,vdYMSxnqpTNlZzaFLfFiRutNo0Lnf6dAf6BjpEJL0iO7zBXsQlvHQ9heyxQfPj0hYbwtsA3SKWg1kn7bULOMQuf7ErKXgumcxsgTCrvV3NUcfJUkGsvIhk9FuWGAGagHPjnvWQdI3KIwxIgtGCvo32NfPElSqGIbrahwLG5uAofv7j9vUiVPIhO3grjBEgSmhXggD22SUxloBdcX546f4GTz4cu6SSqDYJwsYaKCFEDSVQwjqXCgtM3YVSw0mQA,1,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'
2017-07-28 10:26:10 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-28 10:26:10 - DEBUG testThaliMobileNative: 'Server data flushed',
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:with,Error:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C9768882-5104-47E4-8E44-82E70FC67A6A
[ThaliCore] Advertiser: session connected Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C9768882-5104-47E4-8E44-82E70FC67A6A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C9768882-5104-47E4-8E44-82E70FC67A6A
,[ThaliCore] Session.session(_:peer:didChange:) peer:C9768882-5104-47E4-8E44-82E70FC67A6A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C9768882-5104-47E4-8E44-82E70FC67A6A
[ThaliCore] Session.startOutputStream(with:) peer:C9768882-5104-47E4-8E44-82E70FC67A6A
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [2, 7, 8, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (3356 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (3214 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (4451 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received (7714 bytes):'
,2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-28 10:26:19 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-28 10:26:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:10
[ThaliCore] VirtualSocket.closeS,treams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [2, 7, 10]
2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-,28 10:26:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,,"networkType":null}})'
2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:2DEF4005-6540-42F4-B0C,D-F8B75F1A30AB
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:61F798BB-B8AE-4376-B306-D7BF1030062F
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63025
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NxlqwoWN4MerKVexBWpVjbf4O1p6pz9J","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C9768882-5104-47E4-8E44-82E70FC67A6A state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:C9768882-5104-47E4-8E44-82E70FC67A6A
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DCA9EAC-1029-4927-ABDA-5384845F716B state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "2DEF4005-6540-42F4-B0CD-F8B75F1A30AB", generation: 0)
,[ThaliCore] Session.deinit peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:C9768882-5104-47E4-8E44-82E70FC67A6A
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4A18986D-5880-4B35-A4D7-1549C226454F
,[ThaliCore] Browser.startListening
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:26:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BC20BFCE-89C5-4087-9DBF-512405597B19", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:BC20BFCE-89C5-4087-9DBF-512405597B19
,2017-07-28 10:26:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:26:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
2017-07-28 10:26:20 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"61F798BB-B8AE-4376-B306-D7BF1030062F","generation":0}]'
2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"61F798BB-B8AE-4376-B306-D7BF1030062F","generation":0}'
2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2","generation":0}]'
2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2","generation":0}'
2017-07-28 10:26:20 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2", generation: 0)
2017-07-28 10:26:21 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2","generation":0}]'
2017-07-28 10:26:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"441E8F17-C36A-4E5E-8F40-1B59E7D4BCF2","generation":0}'
2017-07-28 10:26:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
[ThaliCore] Br,owser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BC20BFCE-89C5-4087-9DBF-512405597B19:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BC20BFCE-89C5-4087-9DBF-512405597B19", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6230A678-BDFC-47EE-97B5-B204F76EEA87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6230A678-BDFC-47EE-97B5-B204F76EEA87", generation: 0)
2017-07-28 10:26:21 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6230A678-BDFC-47EE-97B5-B204F76EEA87","generation":0}]'
2017-07-28 10:26:21 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"6230A678-BDFC-47EE-97B5-B204F76EEA87","generation":0}'
2017-07-28 10:26:21 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 ,10:26:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:BC20BFCE-89C5-4087-9DBF-5,12405597B19
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:25 ,- DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-28 10:26:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:25 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:73D8A001-48CB-411D-9958-259B1B061671
[ThaliCore] Browser.startListening
,ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "52562FB7-12F5-4729-952D-CE9E8E839E32", generation: 0)
[ThaliCore] Advertise,r.startAdvertising with peerID:52562FB7-12F5-4729-952D-CE9E8E839E32
ok 107 discoveryActive should be false
ok 108 advertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 d,iscoveryActive should be false
ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:52562FB7-12F5-4729-952D-CE9E8E839E32
,ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
,ok 113 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-28 10:26:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 114 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 115 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-28 10:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 116 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 117 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-28 10:26:26 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-28 10:26:27 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-28 10:26:27 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 122 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-28 10:26:27 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:27 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 124 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 126 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:f79dc8ef-2ddb-45bc-8f69-207f396cc0d5 error: startListeningNotActive
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"xw5vSXUJPSSzQ8fqs6rSNpUj8ImiWSQI","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 127 Should only get called after multiConnect returned
,ok 128 SyncValue matches
,ok 129 Got right error
,ok 130 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C9909A8D-EC79-4FB1-910F-E902E132702C
[ThaliCore] Browser.startListening
,2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:26:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 131 No error on starting
ok 132 Got null as expected
2017-07-28 10:26:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LKby1N4v9MT2BlNrAFpbIT68DuyZpIa7","error":"Illegal peerID","portNumber",:null}'
ok 133 Should only get called after multiConnect returned
ok 134 SyncValue matches
ok 135 Got right error
ok 136 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28, 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-28 10:26:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B1E695E9-0544-4305-B5DA-CBB5714C639F
[ThaliCore] Browser.startListening
2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:26:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:26:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 No error on starting
ok 138 Got right error
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"61F798BB-B8AE-4376-B306-D7BF1030062F","generation":0}]'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"61F798BB-B8AE-4376-B306-D7BF1030062F","generation":0}'
,2017-07-28 10:26:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28, 10:26:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to n,ative'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 139 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:30 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:30 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:26:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:c63383f2-ab49-4630-ae1b-a82b3c485b19
ok 140 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:FC4C696C-75CA-4D68-9DED-BD4676EDB25B
2017-07-28 1,0:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 141 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:081E4B09-42B8-4868-95BD-2078A3159137
[Tha,l,iCore] Browser.startListening
2017-07-28 10:26:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:26:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:31 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
2017-07-28 10:26:32 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"61F798BB-B8AE-4376-B306-D7BF1030062F","generation":0}'
2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 61F798BB-B8AE-4376-B306-D7BF1030062F (syncValue: q9bXSD00R26h6UcCFDqwsnGouu4oze5o)'
,2017-07-28 10:26:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FC4C696C-75CA-4D68-9DED-BD4676EDB25B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
2017-07-28 10:26:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5A32A711-3AC9-4795-86B0-CC719851C109","generation":0}'
2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:26:33 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
2017-07-28 10:26:33 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FE8EAE0C-6391-48F3-99B5-6FCC3C505E23","generation":0}'
2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:26:33 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:26:33 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:61,F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,1F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9BF9E82E-695C-411E-AAA6-81F0E3D64ACD
[ThaliCore] Advertiser: session connected Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:9BF9E82E-695C-411E-AAA6-81F0E3D64ACD state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "61F798BB-B8AE-4376-B306-D7BF1030062F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-28 10:26:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"q9bXSD00R26h6UcCFDqwsnGouu4oze5o","error":"Peer is unavailable","portNumber":null}'
,2017-07-28 10:26:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'q9bXSD00R26h6UcCFDqwsnGouu4oze5o', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:26:38 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-28 10:26:38 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5A32A711-3AC9-4795-86B0-CC719851C109 (syncValue: yuFsHfkoxGfp11Sgk141FuTzvb1UCLRL)'
2017-07-28 10:26:38 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:26:38 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:61F798BB-B8AE-4376-B306-D7BF1030062F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9BF9E82E-695C-411E-AAA6-81F0E3D64ACD
,[ThaliCore] Session.session(_:peer:didChange:) peer:9BF9E82E-695C-411E-AAA6-81F0E3D64ACD state: connecting -> connected
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9BF9E82E-695C-411E-AAA6-81F0E3D64ACD
[ThaliCore] Session.startOutput,Stream(with:) peer:9BF9E82E-695C-411E-AAA6-81F0E3D64ACD
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [2, 7, 10, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63041
,2017-07-28 10:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yuFsHfkoxGfp11Sgk141FuTzvb1UCLRL","error":null,"portNumber":63041}'
,2017-07-28 10:26:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yuFsHfkoxGfp11Sgk141FuTzvb1UCLRL', error: 'null', listeningPort: '63041''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
,ok 143 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0) found active relay
,2017-07-28 10:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"B8uhpjBqhNRjONnaS1GPk1wRxhQ4MZ8j","error":null,"portNumber":63041}'
,ok 144 No error
,ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5A32A711-3AC9-4795-86B0-CC719851C109", generation: 0) found active relay
,2017-07-28 10:26:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"icVXfQQ826fU3rv2ZHCs3Q55Bi6drUNz","error":null,"portNumber":63041}'
,ok 147 No error
,ok 148 Ports equal
,# teardown
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 7, 10, 11, 12]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A41F7507-1D1B-4891-849A-21F8E98F3B3A
[ThaliCore] Advertiser: session connected Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:A41F7507-1D1B-4891-849A-21F8E98F3B3A state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:A41F7507-1D1B-4891-849A-21F8E98F3B3A
,[ThaliCore] Session.session(_:peer:didChange:) peer:A41F7507-1D1B-4891-849A-21F8E98F3B3A state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:A41F7507-1D1B-4891-849A-21F8E98F3B3A
[ThaliCore] Session.startOutputStream(with:) peer:A41F7507-1D1B-4891-849A-21F8E98F3B3A
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [2, 7, 10, 11, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-28 10:26:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:26:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:FC4C696C-75CA-4D68-9DED-BD4676EDB25B
2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10,:,26:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed, by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer", UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocke,tDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandl,e,r removed virtual socket vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:11
[ThaliCore] BrowserManager.disconnect peer:5A32A711-3AC9-4795-86B0-CC719851C109
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] BrowserRelay.closeRelay() sta,te:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63041
[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListe,ner.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStream,sHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [2, 7, 10, 12, 13]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exit,ed RunLoop vsID:13
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:12
[ThaliCore] VirtualSocket.deinit vsID:13 [2, 7, 10, 12]
[ThaliCore] Session.disconnect() peer:5A32A711-,3AC9-4795-86B0-CC719851C109:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:12
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:12 [2, 7, 10]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:9BF9E82E-695C-411E-AAA6-81F0E3D64ACD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "FC4C696C-75CA-4D68-9DED-BD4676EDB25B", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:A41F7507-1D1B-4891-849A-21F8E98F3B3A
,[ThaliCore] Session.deinit peer:A41F7507-1D1B-4891-849A-21F8E98F3B3A
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:5A32A711-3AC9-4795-86B0-CC719851C109:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-07-28 10:26:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# initial peer discovery
,2017-07-28 10:26:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:47 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:26:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-28 10:26:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:48 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:26:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-28 10:26:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:49 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-28 10:26:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:49 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-28 10:26:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-28 10:26:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:26:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-28 10:26:51 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:51 - DEBUG createNativeListener: 'listening 63045'
ok 149 Should throw
,# teardown
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:52 - DEBUG createNativeListener: 'listening 63047'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 150 initial connection state should be CONNECTED
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 151 final connection state should be DISCONNECTED
,# teardown
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:52 - DEBUG createNativeListener: 'listening 63050'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 152 tried to connect to right port
,ok 153 failed due to refused connection
,ok 154 routerPortConnectionFailed is emitted
,# teardown
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:52 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:52 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'listening 63054'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 155 Send/recvd #1 should be equal length
,ok 156 Send/recvd #1 should be same
,ok 157 Send/recvd #2 should be equal length
,ok 158 Send/recvd #2 should be same
,ok 159 Should be exactly 2 client sockets
,# teardown
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - close'
2017-07-28 10:26:53, - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close',
2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
2017-07-28 10:26:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection, to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'listening 63059'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 160 socket shouldn't close until after stream
ok 161 incoming remains open
# teardown
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:53 - DEBUG createNativeListener: 'Native Server - close'
2017-07-28 10:26:53, - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:53 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 63063'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 162 we should not have gotten an error
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - cl,ose'
,ok 163 socket shouldn't close until after incoming
ok 164 incoming is cleaned up
# teardown
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 63067'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 165 stream was closed
,ok 166 incoming should survive
,ok 167 mux should have no streams
,# teardown
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 63071'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 168 we should not have gotten an error
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 169 Buffers are identical
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 170 native server is nulled out
,ok 171 native server should be closed
,ok 172 incoming has been removed
,ok 173 Incoming should be done
,ok 174 The mux object should be closed
,ok 175 The mux stream should be closed
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:54 - DEBUG createNativeListener: 'listening 63075'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-28 10:26:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 176 native server is nulled out
,ok 177 native server should be closed
,ok 178 incoming has been removed
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'listening 63127'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 180 Buffers are identical
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 181 server should be fine
,ok 182 server should be open
,ok 183 incoming has been removed
,ok 184 The mux object should be closed
,ok 185 The mux stream should be closed
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'listening 63131'
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 186 we should not have gotten an error
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 187 Buffers are identical
,2017-07-28 10:26:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2017-07-28 10:26:55 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to ,node - 0 - 0 - closed'
2017-07-28 10:26:55 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-28 10:26:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux, - 0 - close'
ok 188 server should be fine
ok 189 server should be open
ok 190 incoming has been removed
ok 191 The mux object should be closed
ok 192 The mux stream should be closed
,# teardown
,2017-07-28 10:26:56 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-28 10:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:56 - DEBUG createNativeListener: 'Native Server - close'
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
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'listening 63134'
ok 196 port must be in range
,# teardown
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'listening 63135'
ok 197 second start should return same port
,# teardown
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-28 10:26:57 - DEBUG createNativeListener: 'listening 63137'
,2017-07-28 10:26:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 198 we should be connected
2017-07-28 10:26:57 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 199 now we are disconnected
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-28 10:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:57 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-28 10:26:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 200 Passed bogus id
2017-07-28 10:26:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 201 Passed good id but bogus port
,2017-07-28 10:26:58 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 202 Passed right context
,ok 203 Right server
,ok 204 No error should be set
,ok 205 Retry should be false
,ok 206 We called close server
,# teardown
,# setup
,# Single local http request
,listening on 63139
,ok 207 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:58 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:26:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:26:58, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 208 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DB174017-018E-4451-84F9-48C81BD7147D
[ThaliCore] Browser.startListening
2017-07-28 10:26:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
,2017-07-28 10:26:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-28 10:26:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
2017-07-28 10:26:59 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FE8EAE0C-6391-48F3-99B5-6FCC3C505E23","generation":0}'
2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FE8EAE0C-6391-48F3-99B5-6FCC3C505E23, (syncValue: 6V5K4VuUGGqg5I1PvcMbkHkwhHfFFKs6)'
,2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BBF8648D-CF32-4B35-8271-410FDEA09399","generation":0}'
2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:26:59 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
2017-07-28 10:27:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"93BE8C3D-4DB1-49AB-B941-42D47D125E6C","generation":0}'
2017-07-28 10:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:27:00 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:27:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,E8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E23:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:FE,8EAE0C-6391-48F3-99B5-6FCC3C505E23:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,E8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FE8EAE0C-6391-48F3-99B5-6FCC3C505E23", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:27:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6V5K4VuUGGqg5I1PvcMbkHkwhHfFFKs6","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:27:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6V5K4VuUGGqg5I1PvcMbkHkwhHfFFKs6', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:27:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:27:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BBF8648D-CF32-4B35-8271-410FDEA09399 (syncValue: 78HHaUxf4HOkpIFGE6XRSi2hiL9UC6oF)'
2017-07-28 10:27:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BBF8648D-CF32-4B35-8271-410FD,EA09399:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:27:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:511BFC48-3654-43A0-B9A7-334003382552
[ThaliCore] Advertiser: session connected Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:511BFC48-3654-43A0-B9A7-334003382552 state: notConnected -> connecting
[ThaliCore] Session.deinit peer:FE8EAE0C-6391-48F3-99B5-6FCC3C505E2,3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:511BFC48-3654-43A0-B9A7-334003382552
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63149
,2017-07-28 10:27:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"78HHaUxf4HOkpIFGE6XRSi2hiL9UC6oF","error":null,"portNumber":63149}'
,2017-07-28 10:27:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '78HHaUxf4HOkpIFGE6XRSi2hiL9UC6oF', error: 'null', listeningPort: '63149''
,[ThaliCore] Session.session(_:peer:didChange:) peer:511BFC48-3654-43A0-B9A7-334003382552 state: connecting -> connected
,ok 210 should be equal
,2017-07-28 10:27:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 93BE8C3D-4DB1-49AB-B941-42D47D125E6C (syncValue: q7WcIjcqfSC1AklVvWb9AXwx3amYSdLh)'
,2017-07-28 10:27:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA
[ThaliCore] Advertiser: session connected Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63153
,2017-07-28 10:27:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"q7WcIjcqfSC1AklVvWb9AXwx3amYSdLh","error":null,"portNumber":63153}'
,2017-07-28 10:27:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'q7WcIjcqfSC1AklVvWb9AXwx3amYSdLh', error: 'null', listeningPort: '63153''
,ok 211 should be equal
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:27:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:BBF8648D-CF32-4B35-8271-410FDEA09399
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63149
[ThaliCore] Session.disconnect() p,eer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63153
,[ThaliCore] Session.disconnect() peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:511BFC48-3654-43A0-B9A7-334003382552 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3ABAD824-E122-4F0A-9CF1-28EC8A70BE0D", generation: 0)
,[ThaliCore] Session.deinit peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserRelay.deinit
,2017-07-28 10:27:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:12 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:12 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple local http requests
,listening on 63155
,ok 212 should be equal
ok 213 should be equal
ok 214 should be equal
# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:8DDA733B-10AA-4885-AA6E-DC3D3527D0AA
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:95F29FF2-0D10-45FD-BF02-EBCF261CB31F
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:13, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Tha,liCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:0CC1D949-3EA0-476F-B1D3-0BC926D5B49B
[ThaliCore] Browser.startListening
2017-07-28 10:27:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adv,e,rtisingActive":true}'
2017-07-28 10:27:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rou,ter":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BBF8648D-CF32-4B35-8271-410FDEA093,99","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BBF8648D-CF32-4B35-8271-410FDEA09399, (syncValue: r2JdEkxVIkmhb4w8Ibf56wqg0mae6Ilm)'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"93BE8C3D-4DB1-49AB-B941-42D47D125E6C","generation":0}'
,2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:27:14 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:93BE8C3D-4DB1-49AB-B941-42D47D125E6C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "93BE8C3D-4DB1-49AB-B941-42D47D125E6C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAv,ailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}'
2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
2017-07-28 10:27:15 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-28 10:27:15 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-28 10:27:15 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F29FF2-0D10-45FD-BF02-EBCF261CB31F:0
[ThaliCore] BrowserM,anager.foundPeerHandler peer:Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BB,F8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,BF8648D-CF32-4B35-8271-410FDEA09399", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "B,BF8648D-CF32-4B35-8271-410FDEA09399", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BBF8648D-CF32-4B35-8271-410FDEA09399", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:27:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"r2JdEkxVIkmhb4w8Ibf56wqg0mae6Ilm","error":"Peer is unavailable","portNumber":null}'
2017-07-28 10:27:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'r2JdEkxVIkmhb4w8Ibf56wqg0mae6Ilm', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:27:20 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:27:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7CEF816A-6CE4-449C-8991-54BCD7BAA133 (syncValue: 5zp6W2lSGRYOKSx1foA1JIK,NGogKeuz5)'
2017-07-28 10:27:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7CEF816A-6CE4-449C-8991-54BCD,7BAA133:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:27:20 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:BBF8648D-CF32-4B35-8271-410FDEA09399:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63169
2017-07-28 10:27:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5zp6W2lSGRYOKSx1foA1JIKNGogKeuz5",,"error":null,"portNumber":63169}'
2017-07-28 10:27:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '5zp6W2lSGRYOKSx1foA1JIKNGogKeuz5', error: 'null', listeningPort: '63169''
,ok 217 should be equal
ok 218 should be equal
ok 219 should be equal
2017-07-28 10:27:23 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95F44C45-7F4B-4ED1-94A3-C1753634B03C (syncValue: EkHUfMqOKd6wAdfBFDKRxd3XkGqxfg8c)'
2017-07-28 10:27:,23 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] Browser,Relay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF
[ThaliCore] Advertiser: session connected Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63175
,2017-07-28 10:27:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EkHUfMqOKd6wAdfBFDKRxd3XkGqxfg8c","error":null,"portNumber":63175}'
,2017-07-28 10:27:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EkHUfMqOKd6wAdfBFDKRxd3XkGqxfg8c', error: 'null', listeningPort: '63175''
,[ThaliCore] Session.session(_:peer:didChange:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF state: connecting -> connected
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E
[ThaliCore] Advertiser: session connected Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E state: connecting -> connected
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-28 10:27:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:95F29FF2-0D10-45FD-BF02-EBCF261CB31F
2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133
[ThaliCore] BrowserRelay.closeRelay(,) state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63169
[ThaliCore] Session.disconnect() peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socke,t error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
,[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
,[ThaliCore] TCPClient.deinit
,[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:20DA17E9-8905-46E1-B602-144EB1DA4CFF state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "95F29FF2-0D10-45FD-BF02-EBCF261CB31F", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0 state: connected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63175
,[ThaliCore] Session.disconnect() peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
,[ThaliCore] Session.deinit peer:C6F6D8C4-4793-4830-9FD0-480DC997D72E
[ThaliCore] Session.deinit peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C
,2017-07-28 10:27:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-28 10:27:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EkHUfMqOKd6wAdfBFDKRxd3XkGqxfg8c","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserRelay.deinit
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 225 specific error should be returned
,# teardown
,ok 226 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:32 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:32 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-28 10:27:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'should be able to call #stopListeningForAdvertisements many times''
,# teardown
,ok 227 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:33 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'listening 63179'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6FF95469-8DAF-4A57-BF41-6F9B8309F821
[ThaliCore] Browser.startListening
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 228 no errors
[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 229 still no errors
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
# teardown
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}]'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:33 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-28 10:27:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 230 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'listening 63180'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9C25B4BA-0608-476F-B8B7-0F6D7A094F34", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:9C25B4BA-0608-476F-B8B7-0F6D7A094F34
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Receive,d state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:2,7:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 231 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9C25B4BA-0608-476F-B8B7-0F6D7A094F34", ge,n,eration: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:9C25B4BA-0608-476F-B8B7-0F6D7A094F34
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nu,ll,"networkType":null}})'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 232 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9C25B4BA-0608-476F-B8B7-0F6D7A094F34
,[ThaliCore] Advertiser.stopAdvertising() peerID:9C25B4BA-0608-476F-B8B7-0F6D7A094F34
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 233 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'listening 63183'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingAct,ive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 no errors
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discover,yAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 235 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 236 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonT,CP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:34 - DEBUG thaliMobi,leNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 237 network status should have certain non-empty properties
,# teardown
,ok 238 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:35 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-28 10:27:35 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 239 specific error expected
,# teardown
,ok 240 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:35 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'listening 63184'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:26165015-78CD-4651-81D3-7D50DF9584CC
[ThaliCore] Browser.st,artListening
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C12BC061-2E1D-4B00-8661-66176E5D04F0", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,C12BC061-2E1D-4B00-8661-66176E5D04F0
2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:35 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:35 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 all connection succeed
,# teardown
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}]'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C12BC061-2E1D-4B00-8661-66176E5D04F0
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 242 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'listening 63187'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3ACF3D4C-5D99-4271-82F1-6EF4F23A7CEB
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "25D9E77D-19EB-4172-9B33-AD54808371D3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:25D9E77D-19EB-4172-9B33-AD54808371D3
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 243 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:25D9E77D-19EB-4172-9B33-AD54808371D3
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-28 10:27:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:36 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:27:36 - DEBUG ,t,haliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper:, 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'listening 63189'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B2BAAB63-708F-4105-BDCD-9B2523ED23C8
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6D6DB92E-4253-4CB9-8C71-449DC4994999", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:6D6DB92E-4253-4CB9-8C71-449DC4994999
2017-07-28 1,0:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6D6DB92E-4253-4CB9-8C71-449DC4994999
,2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28, 10:27:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:27:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 245 is stopped after calling stop
,ok 246 connection should fail after stopping
,# teardown
,ok 247 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-28 10:27:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 248 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 249 error description matches
,# teardown
,ok 250 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:37 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:37 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:37 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-28 10:27:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 251 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 252 error description matches
,# teardown
,ok 253 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:38 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 254 IMPLEMENT ME!!!!!!
,# teardown
,ok 255 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:38 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-28 10:27:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 256 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-28 10:27:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 257 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:39 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-28 10:27:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:39 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:39 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-28 10:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 259 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 260 NOT IMPLEMENTED # SKIP
,# teardown
,ok 261 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:40 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:40 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-28 10:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 262 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:40 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-28 10:27:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 263 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-28 10:27:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 264 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-28 10:27:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 265 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:41 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:41 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:41 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 63192'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CAB6F387-6205-43BB-84AE-98E0D42AA392
[ThaliCore] Browser.st,artListening
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
ok 266 discoveryActive matches
ok 267 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 268 discoveryActive matches
ok 269 advertisingActive matches
2017-07-28 10:27:42 - DEBUG makeIntoCloseAllServer:, 'closeAll called on server'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 63193'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "87A71B02-76CA-4B0E-9959-7208E674F886", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:87A71B02-76CA-4B0E-9959-7208E674F886
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:87A71B02-76CA-4B0E-9959-7208E674F886
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,onTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
ok 273 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-28 10:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 63195'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 274 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'listening 63196'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:41AC70D9-3D1C-4500-B727-FC949801B2A1
[ThaliCore] Browser.st,artListening
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: 'Filtered out discover,yAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F7FB3F7D-6098-45DE-996C-3806B0585C2A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID,:,F7FB3F7D-6098-45DE-996C-3806B0585C2A
2017-07-28 10:27:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-28 10:27:42 - INFO thaliMobile: 'Received state ({"discoveryActi,ve":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:42 - INFO thaliMobile: ,'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
2017-07-28 10:27:43 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
ok 275 portNumber equal null
,# teardown
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}]'
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}'
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC", generation: 0)
,2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","generation":0}]'
2017-07-28 10:27:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","generation":0}'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A:0
2017-07-28 10:27:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","connectionType":"MPCF","peerAvailable":tru,e,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A", generation: 0)
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","generation":0}]'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","generation":0}'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:27:44 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F7FB3F7D-6098-45DE-996C-3806B0585C2A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F7FB3F7D-6098-45DE-996C-3806B0585C2A", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:F7FB3F7D-6098-45DE-996C-3806B0585C2A
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-28 10:27:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
2017-07-28 10:27:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-28 10:27:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'can do HTTP requests between peers''
,# teardown
,ok 277 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:44 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:44 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can still do HTTP requests between peers with coordinator
,2017-07-28 10:27:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'can still do HTTP requests between peers with coordinator''
,# teardown
,ok 278 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-28 10:27:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 279 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:45 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:45 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# test to coordinate connection cut
,# teardown
,ok 280 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:45 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'listening 63198'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2CB17DF6-150C-414C-90C1-D27D16C46E21
,[ThaliCore] Browser.startListening
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:66D1520A-8B85-4C7C-98D7-E64579619E08
,2017-07-28 10:27:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-28 10:27:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
2017-07-28 10:27:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
2017-07-28 10:27:46 - DEBUG t,haliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 95F44C45-7F4B-4ED1-94A3-C1753634B03C (syncValue: LhqmpeCX1eClHRy,ArtFeVDMo8KO2JKMV)'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0) crea,t,ing a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:95F44C45-7F4B-4ED1-94,A3-C1753634B03C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChang,ed event from native layer [{"peerAvailable":true,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}]'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIde,ntifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","peerAvailable":true,"generation":0,",portNumber":null}'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:66D1520A-8B85-4C7C-98D7-E64579619E08:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0323044D-1913-4454-B736-375476473E4A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
2017-07-28 10:27:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","generation":0}]'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","generation":0}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-28 10:27:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
2017-07-28 10:27:46 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","generation":0}]'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","generation":0}'
,2017-07-28 10:27:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-28 10:27:46 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-28 10:27:46 - DEBUG thaliMobileNativeTestUtils: 'We got a pe,er {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:33B53FAA-55A2-4C6A-AF54-F1FDCDD345B5
[ThaliCore] Advertiser: session connected Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:33B53FAA-55A2-4C6A-AF54-F1FDCDD345B5 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:33B53FAA-55A2-4C6A-AF54-F1FDCDD345B5
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
2017-07-28 10:27:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}]'
2017-07-28 10:27:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","generation":0}'
,2017-07-28 10:27:48 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-28 10:27:48 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"95F44C45-7F4B-4ED1-94A3-C1753634B03C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "95F44C45-7F4B-4ED1-94A3-C1753634B03C", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-28 10:27:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LhqmpeCX1eClHRyArtFeVDMo8KO2JKMV","error":"Peer is unavailable","portNumber":null}'
,2017-07-28 10:27:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LhqmpeCX1eClHRyArtFeVDMo8KO2JKMV', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:27:48 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-28 10:27:48 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 7CEF816A-6CE4-449C-8991-54BCD7BAA133 (syncValue: VkOwOZTzK4TAanIP49585YHxLUywXr6Z)'
,2017-07-28 10:27:48 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:95F44C45-7F4B-4ED1-94A3-C1753634B03C:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:33B53FAA-55A2-4C6A-AF54-F1FDCDD345B5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:33B53FAA-55A2-4C6A-AF54-F1FDCDD345B5
[ThaliCore] Session.startOutputStream(with:) peer:33B53FAA-55A2-4C6A-AF54-F1FDCDD345B5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [2, 7, 10, 14]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C,EF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED
[ThaliCore] Advertiser: session connected Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
,2017-07-28 10:27:52 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}]'
,2017-07-28 10:27:52 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","generation":0}'
,2017-07-28 10:27:52 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-28 10:27:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7CEF816A-6CE4-449C-8991-54BCD7BAA133","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED
,[ThaliCore] Session.startOutputStream(with:) peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 7, 10, 14, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:7C,EF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "7CEF816A-6CE4-449C-8991-54BCD7BAA133", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:27:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"VkOwOZTzK4TAanIP49585YHxLUywXr6Z","error":"Peer is unavailable",,"portNumber":null}'
2017-07-28 10:27:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'VkOwOZTzK4TAanIP49585YHxLUywXr6Z', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-28 10:27:54 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-28 10:27:54 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0323044D-1913-4454-B736-375476473E4A (syncValue: LQG5U5XuehtvkPXueH5adJY,24pHXZEyi)'
2017-07-28 10:27:54 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0323044D-1913-4454-B736-37547,6473E4A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:7CEF816A-6CE4-449C-8991-54BCD7BAA133:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0323044D-1913-4454-B736-375476473E4A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0323044D-1913-4454-B736-375476473E4A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0323044D-1913-4454-B736-375476473E4A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63210
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LQG5U5XuehtvkPXueH5adJY24pHXZEyi","error":null,"portNumber":63210}'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LQG5U5XuehtvkPXueH5adJY24pHXZEyi', error: 'null', listeningPort: '63210''
,2017-07-28 10:27:57 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0323044D-1913-4454-B736-375476473E4A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0323044D-1913-4454-B736-375476473E4A:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [2, 7, 10, 14, 15, 16]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:27:57 - DEBUG testUtils: 'Got response data'
2017-07-28 10:27:57 - DEBUG testUtils: 'Got end'
ok 281 response body should match testData
ok 282 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:66D1520A-8B85-4C7C-98D7-E64579619E08
2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
2017-07-28 10:27:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 283 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisi,ngStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:57 ,- DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDid,D,isconnect(_:withError:) client disconnected
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] Brow,serManager.disconnect peer:0323044D-1913-4454-B736-375476473E4A
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:14
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
[ThaliCor,e] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:14
[ThaliCore] VirtualSocket.deinit vsID:14 [2, 7, 10, 15, 16]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disco,nnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [2, 7, 10, 16]
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port,:63210
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:16
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:16
,[ThaliCore] VirtualSocket.deinit vsID:16 [2, 7, 10]
,[ThaliCore] Session.disconnect() peer:0323044D-1913-4454-B736-375476473E4A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0323044D-1913-4454-B736-375476473E4A:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-28 10:27:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-28 10:27:57 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LQG5U5XuehtvkPXueH5adJY24pHXZEyi","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED
,[ThaliCore] Session.session(_:peer:didChange:) peer:33B53FAA-55A2-4C6A-AF54-F1FDCDD345B5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "66D1520A-8B85-4C7C-98D7-E64579619E08", generation: 0)
,[ThaliCore] Session.deinit peer:0323044D-1913-4454-B736-375476473E4A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4437A46E-FCD3-4A6E-9E01-F01E2427C0ED
,# will fail bad PSK connection between peers
,ok 284 FIX ME, PLEASE!!!
,# teardown
,ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We provide notification when a listener dies and we recreate it
,2017-07-28 10:27:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'We provide notification when a listener dies and we recreate it''
,# teardown
,ok 286 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:58 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
,2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:58 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:58 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated
,2017-07-28 10:27:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated''
,# teardown
,ok 287 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:27:59 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-28 10:27:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-28 10:27:59 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-28 10:27:59 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-28 10:27:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,ok 288 ThaliMobile should be stopped
,# #startListeningForAdvertisements should fail if start not called
,ok 289 specific error should be returned
,# teardown
,2017-07-28 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2FC64F5A-7D7B-4139-91E3-BBD9F7112ADC","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28, 10:28:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"873DBB5A-1FEF-40C0-A3FC-FBC889BBA66A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:28:00 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:28:00 - DEBUG th,aliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 290 error should be null
ok 291 error should be null
,# setup
,ok 292 ThaliMobile should be stopped
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 293 specific error should be returned
,# teardown
,ok 294 error should be null
ok 295 error should be null
,# setup
,ok 296 ThaliMobile should be stopped
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-28 10:28:00 - DEBUG thaliMobileNativeWrapper: 'listening 63212'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
ok 297 error should be null
ok 298 error should be null
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive,":false,"advertisingActive":false}'
ok 299 error should be null
ok 300 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-28 10:28:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 301 error should be null
ok 302 error should be null
,# setup
,ok 303 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'listening 63213'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4F147C49-40EC-4428-9A99-D8586A01B866
[ThaliCore] Browser.st,artListening
2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 304 error should be null
ok 305 error should be null
[ThaliCore] BrowserManager.startListe,ningForAdvertisements
2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 308 error should be null
,ok 309 error should be null
,# setup
,ok 310 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'listening 63214'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5E353CF7-97C7-4934-B3CE-1ED1F533C8A3", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:5E353CF7-97C7-4934-B3CE-1ED1F533C8A3
2017-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 311 error should be null
ok 312 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5E353CF7-97C7-4934-B3CE-1ED1F533C8A3", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:5E353CF7-97C7-4934-B3CE-1ED1F533C8A3
20,17-07-28 10:28:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 313 error should be null
ok 314 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5E353CF7-97C7-4934-B3CE-1ED1F533C8A3
[ThaliCore] Advertiser.stopAdvertising() peerID:5E353CF7-97C7-4934-B3CE-1ED1F533C8A3
2017-07-28 10:28:02 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
2017-07-28 10:28:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 315 error should be null
ok 316 error should be null
,# setup
,ok 317 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'listening 63217'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 318 error should be null
,ok 319 error should be null
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 320 error should be null
,ok 321 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-28 10:28:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:28:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 322 error should be null
ok 323 error should be null
,# setup
,ok 324 ThaliMobile should be stopped
,# #start - Causing native or wifi to fail will cause a promise reject 
,2017-07-28 10:28:02 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
,ok 325 This should not cause wifi to fail
ok 326 native router should be bad
,# teardown
,ok 327 error should be null
ok 328 error should be null
,# setup
,ok 329 ThaliMobile should be stopped
,# #start should fail if called twice in a row
,2017-07-28 10:28:02 - DEBUG thaliMobileNativeWrapper: 'listening 63218'
ok 330 first call should succeed
ok 331 first call should succeed
ok 332 specific error should be returned
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-28 10:28:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:28:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 333 error should be null
ok 334 error should be null
,# setup
,ok 335 ThaliMobile should be stopped
,# #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)
,2017-07-28 10:28:03 - DEBUG CoordinatedClient: 'test was skipped, name: '#start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)''
,# teardown
,ok 336 error should be null
,ok 337 error should be null
,# setup
,ok 338 ThaliMobile should be stopped
,# does not emit duplicate discoveryAdvertisingStateUpdate
,2017-07-28 10:28:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
,# teardown
,ok 339 error should be null
ok 340 error should be null
,# setup
,ok 341 ThaliMobile should be stopped
,# does not send duplicate availability changes
,2017-07-28 10:28:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b694da41-506d-4a89-b18d-c4103cfb202f","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 342 should be calle,d once
ok 343 should not have been called more than once
,# teardown
,2017-07-28 10:28:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b694da41-506d-4a89-b18d-c4103cfb202f","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 344 error should be null
ok 345 error should be null
,# setup
,ok 346 ThaliMobile should be stopped
,# can get the network status
,ok 347 network status should have certain non-empty properties
,# teardown
,ok 348 error should be null
,ok 349 error should be null
,# setup
,ok 350 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (native)
,ok 351 we have not added peer to the cache yet
2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bb55b0a0-ddec-4902-a65c-26fa2fbcf14a","connectionType":"MPCF","peerAvailable":true,"generation":0,,"newAddressPort":false}'
ok 352 peer should be available
ok 353 cache contains native peer
2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"bb55b0a0-ddec-4902-a65c-26fa2fbcf14a","connectionTyp,e":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
ok 354 peer should be unavailable
ok 355 peer has been removed from cache
,# teardown
,ok 356 error should be null
ok 357 error should be null
,# setup
,ok 358 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 359 we have not added peer to the cache yet
,2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"88f1d30a-06ec-4583-9640-81b701566ff3","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 360 peer should be a,vailable
ok 361 cache contains wifi peer
2017-07-28 10:28:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"88f1d30a-06ec-4583-9640-81b701566ff3","connectionType":"tcp","peerAvailable":false,"generation":0,"newA,ddressPort":null}'
ok 362 peer should be unavailable
ok 363 peer has been removed from cache
,# teardown
,ok 364 error should be null
ok 365 error should be null
,# setup
,ok 366 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"866fa1ee-3631-4c7e-b3da-dd1d38254c6c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 367 first peer is available
2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"83674ee7-a2dd-48c1-87fa-444435aefe3c","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":,false}'
ok 368 second peer is available
ok 369 first and second peers are different
,# teardown
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"866fa1ee-3631-4c7e-b3da-dd1d38254c6c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28, 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"83674ee7-a2dd-48c1-87fa-444435aefe3c","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 370 error should be null
ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 373 should not be in cache at start
2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f16a246a-a616-495d-b238-550f1fb42133","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 374 peer is available
,# teardown
,2017-07-28 10:28:05 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f16a246a-a616-495d-b238-550f1fb42133","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 375 error should be null
,ok 376 error should be null
,# setup
,ok 377 ThaliMobile should be stopped
,# native available - peer with same port and different generation is cached (BLUETOOTH)
,2017-07-28 10:28:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with same port and different generation is cached (BLUETOOTH)''
,# teardown
,ok 378 error should be null
ok 379 error should be null
,# setup
,ok 380 ThaliMobile should be stopped
,# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
,2017-07-28 10:28:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)''
,# teardown
,ok 381 error should be null
ok 382 error should be null
,# setup
,ok 383 ThaliMobile should be stopped
,# native available - peer with greater generation is cached (MPCF)
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39be07e3-d69f-4f86-8670-262c29ff9303","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 384 peer should be available
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"39be07e3-d69f-4f86-8670-262c29ff9303","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 385 peer should be ,available
ok 386 should store correct generation
,# teardown
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"39be07e3-d69f-4f86-8670-262c29ff9303","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 387 error should be null
ok 388 error should be null
,# setup
,ok 389 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'listening 63219'
2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cdf223fc-e3d2-4a6f-9144-b1bdea323bfa","connectionType":"MPCF","peerAvaila,ble":true,"generation":2,"newAddressPort":false}'
ok 390 discovered correct peer
ok 391 got correct generation
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"cdf223fc-e3d2-4a6f-9144-b1bdea323bfa","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
ok 392 discovered correct peer
ok 393 got correct generation
,# teardown
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"cdf223fc-e3d2-4a6f-9144-b1bdea323bfa","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:28:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 394 error should be null
,ok 395 error should be null
,# setup
,ok 396 ThaliMobile should be stopped
,# native unavailable - new peer is ignored
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'listening 63220'
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c2696ef9-4bd9-4267-9ddd-6dc9bf540142","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 397 discovered available peer
ok 398 peer is available
,# teardown
,2017-07-28 10:28:07 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c2696ef9-4bd9-4267-9ddd-6dc9bf540142","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 399 error should be null
,ok 400 error should be null
,# setup
,ok 401 ThaliMobile should be stopped
,# native unavailable - cached peer is removed
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2d8ab6cc-c1b3-4d02-b226-4cd95fbf0066","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 402 peer should be available
2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2d8ab6cc-c1b3-4d02-b226-4cd95fbf0066","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPor,t":null}'
ok 403 peer should be unavailable
ok 404 should be removed from cache
,# teardown
,ok 405 error should be null
ok 406 error should be null
,# setup
,ok 407 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-28 10:28:08 - DEBUG thaliMobileNativeWrapper: 'listening 63221'
2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"599e38a6-6078-4978-8bda-22c65128120a","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 408 first peer is expected to be available
2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0674b989-ead8-4b09-9173-ad38b6a945be","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 409 second peer is expected to be available
2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0674b989-ead8-,4b09-9173-ad38b6a945be","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 410 peer became unavailable
ok 411 it was wifi peer
2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handle,P,eer {"peerIdentifier":"0674b989-ead8-4b09-9173-ad38b6a945be","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 412 we found peer again
ok 413 it was wifi peer
2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAv,ailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0674b989-ead8-4b09-9173-ad38b6a945be","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 414 peer became unavailable
ok 415 it was wifi peer
,# teardown
,2017-07-28 10:28:08 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"599e38a6-6078-4978-8bda-22c65128120a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-28 10:28:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:28:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 416 error should be null
ok 417 error should be null
,# setup
,ok 418 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
,2017-07-28 10:28:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)''
,# teardown
,ok 419 error should be null
ok 420 error should be null
,# setup
,ok 421 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-28 10:28:09 - DEBUG thaliMobileNativeWrapper: 'listening 63222'
2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e4765faa-1935-4404-a6d6-e7f408c9f9da","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 422 first peer is expected to be available
2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f92f92e5-fa6f-4d62-ac77-8d7fd93c1fbc","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 423 second peer is expected to be available
,2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e4765faa-1935-4404-a6d6-e7f408c9f9da","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 424 pee,r became unavailable
2017-07-28 10:28:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f92f92e5-fa6f-4d62-ac77-8d7fd93c1fbc","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPor,t":null}'
ok 425 peer became unavailable
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 426 error should be null
,ok 427 error should be null
,# setup
,ok 428 ThaliMobile should be stopped
,# multiconnect failure - new peer is ignored (MPCF)
,2017-07-28 10:28:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
,# teardown
,ok 429 error should be null
ok 430 error should be null
,# setup
,ok 431 ThaliMobile should be stopped
,# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
,2017-07-28 10:28:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 432 error should be null
ok 433 error should be null
,# setup
,ok 434 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"85e03095-8fc6-4213-b44f-e98d620373a7","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 435 peer discovered ,first time does not have new address
2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"85e03095-8fc6-4213-b44f-e98d620373a7","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddres,sPort":false}'
ok 436 address has not been changed
2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"85e03095-8fc6-4213-b44f-e98d620373a7","connectionType":"tcp","peerAvailable":true,"generation,":20,"newAddressPort":true}'
ok 437 new port handled correctly
2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"85e03095-8fc6-4213-b44f-e98d620373a7","connectionType":"tcp","peerAvailable":tru,e,,"generation":20,"newAddressPort":true}'
ok 438 new host handled correctly
2017-07-28 10:28:10 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"85e03095-8fc6-4213-b44f-e98d620373a7","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
ok 439 newAddressPort is null for unavailable peers
,# teardown
,ok 440 error should be null
ok 441 error should be null
,# setup
,ok 442 ThaliMobile should be stopped
,# newAddressPort field (BLUETOOTH)
,2017-07-28 10:28:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort field (BLUETOOTH)''
,# teardown
,ok 443 error should be null
ok 444 error should be null
,# setup
,ok 445 ThaliMobile should be stopped
,# newAddressPort field (MPCF)
,ok 446 NOT IMPLEMENTED # SKIP
,# teardown
,ok 447 error should be null
ok 448 error should be null
,# setup
,ok 449 ThaliMobile should be stopped
,# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
,2017-07-28 10:28:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)''
,# teardown
,ok 450 error should be null
ok 451 error should be null
,# setup
,ok 452 ThaliMobile should be stopped
,# #getPeerHostInfo - error when peer has not been discovered yet
,ok 453 should be equal
,# teardown
,ok 454 error should be null
ok 455 error should be null
,# setup
,ok 456 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)
,2017-07-28 10:28:11 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 457 error should be null
ok 458 error should be null
,# setup
,ok 459 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 460 contains expected properties
ok 461 the same ho,stAddress
ok 462 the same portNumber
,# teardown
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 463 error should be null
ok 464 error should be null
,# setup
,ok 465 ThaliMobile should be stopped
,# #getPeerHostInfo - returns discovered cached wifi peer
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 466 contains expected properties
ok 467 the same hostAddress
ok 468 the same portNumber
,# teardown
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"foo","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 469 error should be null
ok 470 error should be null
,# setup
,ok 471 ThaliMobile should be stopped
,# #disconnect fails on wifi peers
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'listening 63223'
2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6423eeae-079a-4a5f-bffb-0224fd465573","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
ok 472 Got specific error message
,# teardown
,2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6423eeae-079a-4a5f-bffb-0224fd465573","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore], AdvertiserManager.stopAdvertising()
2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:28:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server',
,ok 473 error should be null
ok 474 error should be null
,# setup
,ok 475 ThaliMobile should be stopped
,# #disconnect delegates native peers to the native wrapper
,2017-07-28 10:28:12 - DEBUG thaliMobileNativeWrapper: 'listening 63224'
2017-07-28 10:28:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ca97f90f-3fcc-42ca-bdd0-cf4d2b503ac5","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
[ThaliCore] BrowserManager.disconnect peer:ca97f90f-3fcc-42ca-bdd0-cf4d2b503ac5
ok 476 native wrapper `disconnect` called once
ok 477 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-28 10:28:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ca97f90f-3fcc-42ca-bdd0-cf4d2b503ac5","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-28 10:28:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-28 10:28:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 478 error should be null
,ok 479 error should be null
,# setup
,ok 480 ThaliMobile should be stopped
,# network changes emitted correctly
,2017-07-28 10:28:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes emitted correctly''
,# teardown
,ok 481 error should be null
ok 482 error should be null
,# setup
,ok 483 ThaliMobile should be stopped
,# network changes not emitted in started state
,2017-07-28 10:28:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in started state''
,# teardown
,ok 484 error should be null
ok 485 error should be null
,# setup
,ok 486 ThaliMobile should be stopped
,# network changes not emitted in stopped state
,2017-07-28 10:28:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'network changes not emitted in stopped state''
,# teardown
,ok 487 error should be null
ok 488 error should be null
,# setup
,ok 489 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on Android
,2017-07-28 10:28:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on Android''
,# teardown
,ok 490 error should be null
ok 491 error should be null
,# setup
,ok 492 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-28 10:28:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 493 error should be null
ok 494 error should be null
,# setup
,ok 495 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-28 10:28:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 496 error should be null
ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# does not fire duplicate events after peer listener recreation
,2017-07-28 10:28:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'does not fire duplicate events after peer listener recreation''
,# teardown
,ok 499 error should be null
ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# #stop should change peers
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'listening 63225'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EC3D0109-909F-4CA3-8148-34DE4C536E87
[ThaliCore] Browser.startListening
2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"19c8dfa4-cd80-4ded-8244-99411feb7c6a","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 502 Peer availabilities has one entry for our connection type
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8f52c2cd-faca-4cb9-b8ac-d8aacf91fb61","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 503 Peer availabilities has one entry for our connection type
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"19c8dfa4-cd80-4ded-8244-99411feb7c6a","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8f52c2cd-faca-4cb9-b8ac-d8aacf91fb61","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,111],"networkType":"BOTH"}})'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-28 10:28:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 504 No peers
,ok 505 No peers
,ok 506 No peers
,# teardown
,ok 507 error should be null
,ok 508 error should be null
,# setup
,ok 509 ThaliMobile should be stopped
,# If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted
,2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'listening 63226'
2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4f017232-927e-4ef3-9658-ce08ff96d291","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 510 1
ok 511 2
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e5d10240-1091-449c-b50b-8aa3529d49fc","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-28 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4f017232-927e-4ef3-9658-ce08ff96d291","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28, 10:28:16 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"e5d10240-1091-449c-b50b-8aa3529d49fc","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Advertis,erManager.stopAdvertising()
2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingState,Update (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-28 10:28:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10,:,28:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:28:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 512 error should be null
ok 513 error should be null
,# setup
,ok 514 ThaliMobile should be stopped
,# peer should be found once after listening and discovery started
,2017-07-28 10:28:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer should be found once after listening and discovery started''
,# teardown
,ok 515 error should be null
,ok 516 error should be null
,# setup
,ok 517 ThaliMobile should be stopped
,# can get data from all participants
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'listening 63227'
,ok 518 error should be null
,ok 519 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9D650D87-8C6C-4AED-A3AE-5132A5710C9F
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 520 error should be null
,ok 521 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6BD7F164-BD3A-436A-AFCD-AC81A7D7C7D7
[ThaliCore] Browser.startListening
,2017-07-28 10:28:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 522 error should be null
,ok 523 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","generation":0}]'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","generation":0}'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 16CAC7EF-BA00-4A94-865C-8B233DBD72F1 (syncValue: 0)'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "16,CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D650D87-8C6C-4AED-A3AE-5132A5710C9F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Advertiser: session connected Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0)
2017-07-28 10:28:18 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","generation":0}]'
2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","peerAvail,able":true,"generation":0,"portNumber":null}'
2017-07-28 10:28:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","connectionType":"MPCF","peerAvailable":true,"generation":0,",newAddressPort":false}'
2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}]'
2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-28 10:28:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0323044D-1913-4454-B736-375476473E4A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","generation":0}]'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","generation":0}'
,2017-07-28 10:28:18 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:28:18 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
,[ThaliCore] Session.session(_:peer:didChange:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,6CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Session.startOutputStream(with:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,7 [2, 7, 10, 17]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,6CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,6CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:16,CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "16CAC7EF-BA00-4A94-865C-8B233DBD72F1", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1 error: max retries exceeded
2017-07-28 10:28:28 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Connection could not be established","portNumber":null}'
,2017-07-28 10:28:28 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for DD0D4E6E-B98D-47EB-BD63-5DD28772CB37 (syncValue: 1)'
2017-07-28 10:28:28 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] Session.deinit peer:16CAC7EF-BA00-4A94-865C-8B233DBD72F1:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DD0D4E6E-B98D-47EB-BD63-5DD28772CB37", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63239
2017-07-28 10:28:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":null,"portNumber":63239,}'
,2017-07-28 10:28:31 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 2)'
2017-07-28 10:28:31 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DD0D4E6E-B98D-47EB-BD63-5DD28772CB37:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [2, 7, 10, 17, 18]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] Advertiser: session connected Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:701D18EE-61FC-4884-9394-6931A9342548 state: notConnected -> connecting
,2017-07-28 10:28:31 - DEBUG testUtils: 'Got response data'
2017-07-28 10:28:31 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63243
2017-07-28 10:28:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":63243,}'
,2017-07-28 10:28:34 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0323044D-1913-4454-B736-375476473E4A (syncValue: 3)'
2017-07-28 10:28:34 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0323044D-1913-4454-B736-375476473E4A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [2, 7, 10, 17, 18, 19]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:28:34 - DEBUG testUtils: 'Got response data'
,2017-07-28 10:28:34 - DEBUG testUtils: 'Got end'
,ok 524 received all uuids
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] Session.session(_:peer:didChange:) peer:701D18EE-61FC-4884-9394-6931A9342548 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] Session.startOutputStream(with:) peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,0 [2, 7, 10, 17, 18, 19, 20]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0323044D-1913-4454-B736-375476473E4A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
,2017-07-28 10:28:34 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","generation":0}]'
,2017-07-28 10:28:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","generation":0}'
,2017-07-28 10:28:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-28 10:28:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0323044D-1913-4454-B736-375476473E4A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-28 10:28:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"16CAC7EF-BA00-4A94-865C-8B233DBD72F1","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:28:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"DD0D4E6E-B98D-47EB-BD63-5DD28772CB37","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:28:35 ,- DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:18
[ThaliCore] VirtualSocket.closeStreams() vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:18
[Th,aliCore] VirtualSocket.deinit vsID:18 [2, 7, 10, 17, 19, 20]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.d,idSocketDisconnectHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:19
[Th,aliCore] VirtualSocket.deinit vsID:19 [2, 7, 10, 17, 20]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSo,cketDisconnectHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:0323044D-1913-4454-B736-375476473E4A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:03,23044D-1913-4454-B736-375476473E4A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,323044D-1913-4454-B736-375476473E4A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0323044D-1913-4454-B736-375476473E4A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-28 10:28:36 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Peer is unavailable","portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9D650D87-8C6C-4AED-A3AE-5132A5710C9F
2017-07-28 10:28:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-28 10:28:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,}})'
2017-07-28 10:28:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-28 10:28:36 - DEBUG thaliMobileN,ativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-28 10:28:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-28 10:28:36 - DEBUG makeInt,oCloseAllServer: 'closeAll called on server'
ok 525 error should be null
ok 526 error should be null
# setup
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeS,treams() vsID:17
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket c,losed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Adve,rtiserRelay.didSocketDisconnectHandler removed virtual socket vsID:20
[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] VirtualSocket.deinit vsID:17 [2, 7, 10, 20]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] VirtualSocket.deinit vsID:20 [2, 7, 10]
,[ThaliCore] Session.deinit peer:0323044D-1913-4454-B736-375476473E4A:0
[ThaliCore] BrowserRelay.deinit
,ok 527 ThaliMobile should be stopped
,# test for data corruption
,2017-07-28 10:28:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 528 error should be null
,ok 529 error should be null
,# setup
,# #testThaliPeerAction - test getters
,ok 530 getPeerIdentifier
ok 531 getConnectionType
ok 532 getActionType
ok 533 getActionState
ok 534 getPskIdentity
ok 535 getPskKey
,# teardown
,# setup
,# #testThaliPeerAction - start and kill
,ok 536 initial state
,ok 537 after start
,2017-07-28 10:28:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 538 after kill
,# teardown
,# setup
,# #testThaliPeerAction - double start
,ok 539 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - start after kill
,2017-07-28 10:28:38 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 540 clean kill
,ok 541 should be equal
,# teardown
,# setup
,# #testThaliPeerAction - make sure ids are unique
,ok 542 should not be equal
,# teardown
,# setup
,# #testThaliPeerAction - check that forever agent can be destroyed
,ok 543 forever agent should have it's own destroy method
ok 544 agent's destroy should be called
ok 545 agent's destroy should not be called again
ok 546 agent is destroyed
,# teardown
,# setup
,# Test PeerDictionary basic functionality
,ok 547 Entry counter must be 1
,ok 548 Entry exists
ok 549 Size must be 1
ok 550 Entry counter must be 2
ok 551 Entry exists
ok 552 Size must be 2
ok 553 Entry counter must be 1
ok 554 Entry exists
ok 555 Size must be 3
ok 556 Entry counter must be 2
ok 557 Entry exists
ok 558 Size must be 4
ok 559 Entry 1_1 should not be found
ok 560 Entry 1_1 does not exist
ok 561 Size must be 3
,ok 562 Entry 1_2 should not be found
,ok 563 Entry 1_2 does not exist
,ok 564 Size must be 2
,ok 565 should be equal
,ok 566 Entry 2_1 should not be found
,ok 567 Entry 2_2 should not be found
,ok 568 Entry 2_1 does not exist
,ok 569 Entry 2_2 does not exist
,ok 570 Size must be 0
,# teardown
,# setup
,# Test PeerDictionary with multiple entries.
,ok 571 Size must be100
,ok 572 Entries between 20 and MAXSIZE + 20 should exist
,ok 573 WAITING state entry should not be removed
,# teardown
,# setup
,# RESOLVED entries are removed before WAITING state entry.
,ok 574 Entries between 6 and MAXSIZE + 4 should exist
,ok 575 Size should be MAXSIZE
,ok 576 Size should be MAXSIZE+6
,# teardown
,# setup
,# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
,ok 577 WAITING state entry should not be removed
,ok 578 Waiting entries between 6 and MAXSIZE + 4 should exist
,ok 579 Size should be MAXSIZE
,ok 580 entryCounter should be MAXSIZE+6
,# teardown
,# setup
,# When CONTROLLED_BY_POOL entry is removed and kill is called.
,ok 581 Kill should be called once
,ok 582 Size should be MAXSIZE
,# teardown
,# setup
,# #ThaliPeerPoolDefault - single action
,ok 583 is an agent
ok 584 enqueue is fine
ok 585 Everything should be off the queue
,# teardown
,# setup
,# #ThaliPeerPoolDefault - multiple actions
,ok 586 is an agent
ok 587 first enqueue is fine
,ok 588 is an agent
ok 589 second enqueue is fine
ok 590 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 591 Queue is empty
,# teardown
,# setup
,# #ThaliPeerPoolDefault - PSK Pool works
,ok 592 is an agent
ok 593 good enqueue
,ok 594 Identity should match
,2017-07-28 10:28:43 - DEBUG testUtils: 'Got response data'
,2017-07-28 10:28:43 - DEBUG testUtils: 'Got end'
,ok 595 Got expected response
,ok 596 Got psk call back
,# teardown
,2017-07-28 10:28:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #ThaliPeerPoolDefault - stop
,ok 597 is an agent
,ok 598 enqueue worked
,ok 599 is an agent
,ok 600 enqueue 2 worked
,ok 601 enqueue is not available when stopped
,ok 602 start action is killed
,ok 603 killed action is still killed
,ok 604 enqueued action when stopped is killed
,ok 605 inQueue is empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that start verifies queue length
,ok 606 good start
ok 607 good enqueue
ok 608 queue is not empty
,# teardown
,# setup
,# #ThaliPeerPoolInterface - bad enqueues
,ok 609 null arg
ok 610 wrong arg type
ok 611 wrong arg type
,# teardown
,# setup
,# #ThaliPeerPoolInterface - do not allow same object type
,ok 612 good enqueue
,ok 613 already enqueued
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
,ok 614 good enqueue
ok 615 2nd good enqueue
ok 616 we are in the pool
ok 617 We are out of the pool
ok 618 Action was killed
ok 619 The original kill was called too
ok 620 second item is still in queue
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
,ok 621 good enqueue
ok 622 first kill
ok 623 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 624 1st good enqueue
,ok 625 2nd good enqueue
ok 626 1st action is in the pool
ok 627 2nd action is in the pool
ok 628 1st action is out of the pool
ok 629 2st action is out of the pool
ok 630 pool is empty
,# teardown
,# setup
,# We reject unrecognized connection type
,2017-07-28 10:28:46 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 631 Got right error
,ok 632 Start should not be called
,ok 633 Kill should have been called at least once
,# teardown
,# setup
,# We reject unrecognized action type
,2017-07-28 10:28:47 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-28 10:28:47 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
,ok 634 Got right error
,ok 635 Start should not be called
,ok 636 Kill should have been called at least once
,# teardown
,# setup
,# One action on bluetooth
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 637 Got null
2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier,: peerID'
ok 638 is an agent
2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 587, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
,ok 639 Got killed at least once
,# teardown
,# setup
,# Two notification actions
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 640 Got Null
,ok 641 Got another null
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,ok 642 is an agent
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 588, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 643 is an agent
,2017-07-28 10:28:49 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 589, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
,ok 644 Action 1 killed at least once
,ok 645 Action 1 went first
,ok 646 Action 2 killed at least once
,# teardown
,# setup
,# replicateThroughProblems
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 647 should have gotten null
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
,ok 648 Should have stopped nicely
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
,ok 649 Still looking for null
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,ok 650 Yup, another null
,ok 651 We cloned!
,# teardown
,# setup
,# Replication goes first
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,ok 652 Null 1
ok 653 (unnamed assert)
2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 654 is an agent
ok 655 ,Null 3
ok 656 Replication not yet called
ok 657 Notification 2 not yet called
2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBluetoot,h, Peer Identifier: notificationAction'
2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
ok 658 is an agent
ok 659, Notification went first
ok 660 Notification 2 not called yet
,2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2017-07-28 10:28:50 - DEBUG thaliPeerPoo,lOneAtATime: 'Got a replication response with no error!'
2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 661 is, an agent
ok 662 Notification finished
ok 663 Replication finished
2017-07-28 10:28:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 592, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Ide,ntifier: notificationAction'
,# teardown
,# setup
,# wifi allows many parallel non-replication actions
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,ok 664 is an agent
,ok 665 First does not throw
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,ok 666 is an agent
,ok 667 Second does not throw
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 594, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
,truetruefalsetrue
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 593, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
,truetruetruetrue
,# teardown
,# setup
,# wifi allows no more than 2 simultaneous replication actions for same peerID
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 668 is an agent
,ok 669 first ok
,2017-07-28 10:28:51 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,ok 670 is an agent
,ok 671 second ok
,ok 672 third ok
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 595, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 596, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,2017-07-28 10:28:52 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
,# teardown
,# setup
,# Client to server request coordinated
,2017-07-28 10:28:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Client to server request coordinated''
,# teardown
,2017-07-28 10:28:52 - INFO testThaliNotification: 'Participants:0 Peers Replied to us:0 Peers requested to:0'
,# setup
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 673 peerIdentifier should match
ok 674 generation should match
,ok 675 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 676 good beacon
,ok 677 good preAmble
,ok 678 public keys match!
,ok 679 must return null after successful call
,ok 680 Once start returns the action should be in KILLED state
,# teardown
,2017-07-28 10:28:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test HTTP_BAD_RESPONSE locally
,2017-07-28 10:28:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test HTTP_BAD_RESPONSE locally''
,# teardown
,2017-07-28 10:28:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test NETWORK_PROBLEM locally
,ok 681 Response should be NETWORK_PROBLEM
,ok 682 reject reason should be: Could not establish TCP connection
,# teardown
,2017-07-28 10:28:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails when getPeerHostInfo fails
,ok 683 Resolution should be BAD_PEER
,ok 684 correct error message
,# teardown
,2017-07-28 10:28:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the start two times
,ok 685 Call start once
,ok 686 Response should be BEACONS_RETRIEVED_AND_PARSED
,ok 687 must return null after successful call.
,# teardown
,2017-07-28 10:28:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill before calling the start
,ok 688 Should be Killed
,ok 689 Start after killed
,# teardown
,2017-07-28 10:28:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill immediately after the start
,ok 690 Should be KILLED
,ok 691 must return null after successful kill
,# teardown
,2017-07-28 10:28:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Call the kill while waiting a response from the server
,ok 692 Should be KILLED
ok 693 must return null after successful kill
,# teardown
,2017-07-28 10:29:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test to exceed the max content size locally
,ok 694 HTTP_BAD_RESPONSE should be response when content size is exceeded
,ok 695 must return null after successful call
,# teardown
,2017-07-28 10:29:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Close the server socket while the client is waiting a response from the server. Local test.
,2017-07-28 10:29:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 696 Should be NETWORK_PROBLEM caused closing server socket
ok 697 Should be Could not establish TCP connection
,# teardown
,# setup
,# Close the client socket while the client is waiting a response from the server. Local test.
,ok 698 Should be NETWORK_PROBLEM caused closing client socket
ok 699 Should be Could not establish TCP connection
,# teardown
,2017-07-28 10:29:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# #generatePreambleAndBeacons bad args
,ok 700 publicKeysToNotify cannot be null
ok 701 ecdh for local device cannot be null
ok 702 milliseconds cannot be less than 0
ok 703 milliseconds cannot be 0
ok 704 milliseconds cannot be greater than one_day
,# teardown
,# setup
,# #generatePreambleAndBeacons empty keys to notify
,ok 705 should be equal
,# teardown
,# setup
,# #generatePreambleAndBeacons multiple keys to notify
,ok 706 should be equal
,ok 707 should be equal
,ok 708 (unnamed assert)
ok 709 should be equal
,# teardown
,# setup
,# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
,ok 710 should throw
,# teardown
,# setup
,# #parseBeacons invalid expiration in beaconStreamWithPreAmble
,ok 711 Preamble expiration must be a 64 bit integer
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 712 Expiration out of range
,# teardown
,# setup
,# #parseBeacons expiration out of range lower
,ok 713 Expiration out of range
,# teardown
,# setup
,# #parseBeacons no beacons returns null
,ok 714 should be equal
,# teardown
,# setup
,# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
,ok 715 Malformed encrypted beacon key ID
,# teardown
,# setup
,# #parseBeacons addressBookCallback fails decrypt
,ok 716 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns no matches
,2017-07-28 10:29:14 - DEBUG CoordinatedClient: 'test was skipped, name: '#parseBeacons addressBookCallback returns no matches''
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns spurious match
,ok 717 should be equal
,ok 718 should be equal
,# teardown
,# setup
,# #parseBeacons addressBookCallback returns public key
,ok 719 right number of calls to address book
,ok 720 good preAmble
,ok 721 good unencryptedKeyId
,ok 722 good beacon
,# teardown
,# setup
,# validate generatePskIdentityField
,ok 723 decoded buffers match
,# teardown
,# setup
,# validate generatePskSecret
,ok 724 secrets match
,# teardown
,# setup
,# validate generatePskSecrets
,ok 725 Matching numbers
,ok 726 We have an entry!
ok 727 keys match
,ok 728 secrets match
,ok 729 We have an entry!
,ok 730 keys match
,ok 731 secrets match
,ok 732 We have an entry!
,ok 733 keys match
,ok 734 secrets match
,# teardown
,# setup
,# validate generateBeaconStreamAndSecrets
,ok 735 Streams have same length
,ok 736 matching size
,ok 737 keys match
,ok 738 secrets match
,# teardown
,# setup
,# Add two Peers.
,ok 739 should be equal
ok 740 peerDictionalty contains 2 peers
ok 741 bluetooth peer's notification has correct connection type
ok 742 tcp peer's notification has correct connection type
,2017-07-28 10:29:19 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
2017-07-28 10:29:19 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-28 10:29:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# TCP_NATIVE peer loses DNS
,ok 743 notification peer dictionary contains exactly 1 peer
,2017-07-28 10:29:19 - WARN thaliNotificationClient: 'peer is not available'
,ok 744 notification peer dictionary does not contain any peers
,2017-07-28 10:29:19 - DEBUG thaliPeerPoolDefault: 'Got err   peer not available'
,# teardown
,2017-07-28 10:29:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Received beacons with no values for us
,ok 745 entry exists
,ok 746 entry is resolved
,# teardown
,2017-07-28 10:29:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Notification action killed with a superseded
,ok 747 Action should be KILLED
,ok 748 Peer state should be RESOLVED
,# teardown
,2017-07-28 10:29:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 749 hostAddress must match
,ok 750 portNumber must match
,ok 751 suggestedTCPTimeout must match
,ok 752 connectionType must match
,ok 753 peerIDs must match
,# teardown
,2017-07-28 10:29:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 754 Correct error
,# teardown
,2017-07-28 10:29:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally using ThaliPeerPoolDefault
,ok 755 hostAddress must match
,ok 756 portNumber must match
,ok 757 suggestedTCPTimeout must match
,ok 758 connectionType must match
,ok 759 peerIds must match
,# teardown
,2017-07-28 10:29:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Action fails because of a bad hostname.
,2017-07-28 10:29:23 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 760 action should be resolved with NETWORK_PROBLEM error
,2017-07-28 10:29:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 761 action should be resolved with NETWORK_PROBLEM error
,2017-07-28 10:29:24 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 762 action should be resolved with NETWORK_PROBLEM error
,2017-07-28 10:29:25 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 763 action should be resolved with NETWORK_PROBLEM error
,ok 764 correct number of requests
,ok 765 correct number of failures
,ok 766 correct final peer state
,# teardown
,2017-07-28 10:29:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# hostaddress is removed when the action is running. 
,2017-07-28 10:29:27 - WARN thaliNotificationClient: 'peer is not available'
,2017-07-28 10:29:27 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 767 peerDictionary should become empty
,# teardown
,2017-07-28 10:29:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-28 10:29:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 768 failed with expected error
ok 769 peer state should be RESOLVED
,# teardown
,2017-07-28 10:29:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notification client correctly handles peer availability changes of the same peer
,2017-07-28 10:29:28 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 770 First action failed
,ok 771 second action killed
# teardown
,2017-07-28 10:29:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Client to server request locally
,ok 772 secrets are equal
,ok 773 Public key matches with the server key
,ok 774 hostAddress must match
,ok 775 portNumber must match
,ok 776 suggestedTCPTimeout must match
,ok 777 connectionType must match
,# teardown
,2017-07-28 10:29:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 778 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
,ok 779 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
,ok 780 All entries should be expired after 1 second
# teardown
,2017-07-28 10:29:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache getSecret and getPublic
,ok 781 All keys need to be available in the cache
,ok 782 All entries should be expired after 1 second
# teardown
,2017-07-28 10:29:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache multiple entries
,ok 783 Size of the cache should be 2
ok 784 Cache doesn't contain dictionary1
,ok 785 Size of the cache should be 1
ok 786 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
,2017-07-28 10:29:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start and stop ThaliNotificationServer
,ok 787 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
,ok 788 ThaliMobile.StopAdvertisingAndListeningshould be called once
,# teardown
,2017-07-28 10:29:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty array to ThaliNotificationServer.start
,ok 789 StartUpdateAdvertisingAndListening should not be called
,ok 790 ThaliMobile.StopAdvertisingAndListening should be called once
,ok 791 no error
,ok 792 should be 204
,# teardown
,2017-07-28 10:29:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass a string to ThaliNotificationServer.start
,ok 793 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-28 10:29:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Pass an empty parameter to ThaliNotificationServer.start
,ok 794 StartUpdateAdvertisingAndListening should not be called
,# teardown
,2017-07-28 10:29:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons
,ok 795 no error
,ok 796 should be 200
,ok 797 should be equal
,ok 798 should be equal
,ok 799 (unnamed assert)
,ok 800 no error
,ok 801 should be 204
,# teardown
,2017-07-28 10:29:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 802 error should be null
,ok 803 should be 204
,# teardown
,2017-07-28 10:29:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeaconsbefore calling start
,ok 804 should be 404
,# teardown
,2017-07-28 10:29:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure peerDictionaryKey is reasonable
,ok 805 equal keys
ok 806 not equal connection type
ok 807 same connection type, different buffer
,# teardown
,# setup
,# Make sure start works
,2017-07-28 10:29:42 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 808 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 809 second cleared dictionary
2017-07-28 10:29:43 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 810 First start and on called correctly
,ok 811 First stop and removeListener called correctly
ok 812 first action kill called
ok 813 second action kill called
,ok 814 first cleared dictionary
ok 815 first cleared pool
ok 816 second cleared dictionary
ok 817 second cleared pool
,# teardown
,# setup
,# Emits error event when peerPool.enqueue throws
,ok 818 Correct error
,# teardown
,# setup
,# Simple peer event
,2017-07-28 10:29:44 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 819 listener has been set
,ok 820 peer dictionary has expected number of entries
,ok 821 Dictionary and pool have same action
,ok 822 ads match
,ok 823 PouchDB matches
,ok 824 DB Names match
,ok 825 public keys match
,ok 826 peer dictionary has expected number of entries
,ok 827 Dictionary and pool have same action
,ok 828 ads match
,ok 829 PouchDB matches
,ok 830 DB Names match
,ok 831 public keys match
,2017-07-28 10:29:44 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
,ok 832 start called once
,ok 833 One entry left
,ok 834 Dictionary and pool have same action
,ok 835 Start never called
,ok 836 Kill called once
,ok 837 no entries left
,ok 838 Third action is dead
,ok 839 peer dictionary has expected number of entries
,ok 840 Dictionary and pool have same action
,ok 841 ads match
,ok 842 PouchDB matches
,ok 843 DB Names match
,ok 844 public keys match
,# teardown
,# setup
,# Coordinated pull replication from notification test
,2017-07-28 10:29:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated pull replication from notification test''
,# teardown
,# setup
,# Server is not there
,2017-07-28 10:29:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-28 10:29:45 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
,2017-07-28 10:29:45 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
,ok 845 right error
,# teardown
,2017-07-28 10:29:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server accepts & closes connection
,2017-07-28 10:29:47 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
,2017-07-28 10:29:47 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
,ok 846 right error
,# teardown
,2017-07-28 10:29:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 500
,2017-07-28 10:29:48 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
,2017-07-28 10:29:48 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 847 Got error as expected
,# teardown
,2017-07-28 10:29:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 401
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 848 Got error as expected
,# teardown
,2017-07-28 10:29:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Server always returns 403
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
,2017-07-28 10:29:49 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
,ok 849 Got error as expected
,# teardown
,2017-07-28 10:29:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with same name as local db
,2017-07-28 10:29:51 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:29:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:29:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 850 should be equal
ok 851 All tests passed!
,# teardown
,2017-07-28 10:29:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure docs replicate with remote db with different name than local db
,2017-07-28 10:29:57 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:29:58 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:30:00 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but we are already killed and so we ignored it'
,ok 852 should be equal
,ok 853 All tests passed!
,# teardown
,2017-07-28 10:30:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do nothing and make sure we time out
,2017-07-28 10:30:03 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,2017-07-28 10:30:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-28 10:30:04 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
ok 854 action should be killed
ok 855 Error should be timed out
,ok 856 No doc found
,# teardown
,2017-07-28 10:30:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Do something and make sure we time out
,2017-07-28 10:30:06 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,2017-07-28 10:30:06 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,ok 857 should be equal
,2017-07-28 10:30:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-28 10:30:08 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,ok 858 action should be killed
ok 859 Error should be timed out
,# teardown
,2017-07-28 10:30:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Start replicating and then catch error when server goes
,ok 860 socket hung up
,# teardown
,2017-07-28 10:30:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make sure clone works
,ok 861 same getPeerAdvertisesDataForUs
,ok 862 Same pouchdB
ok 863 same localDbName
ok 864 Same public key
,# teardown
,# setup
,# Coordinated replication action test - each device has the same local db name
,2017-07-28 10:30:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Coordinated replication action test - each device has the same local db name''
,# teardown
,# setup
,# Coordinated replication action test - each device has different local db name
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'listening 63373'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FED41591-EF39-4DE7-A7B3-7F5E7F60CE6C
[ThaliCore] Browser.startListening
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:538E926E-B201-4924-A207-2E81E539D7B5
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Session.startOutputStream(with:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [2, 7, 10, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:21
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] VirtualSocket.deinit vsID:21 [2, 7, 10]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Session.startOutputStream(with:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,2 [2, 7, 10, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22
[ThaliCore] VirtualSocket.deinit vsID:22 [2, 7, 10]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Session.startOutputStream(with:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,3 [2, 7, 10, 23]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=2 "No such file or directory" UserInfo={NSLocalizedDescription=No such file or directory, NSLocalizedFailureReason=Error ,in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:23
[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [2, 7, 10]
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
2017-07-28 10:30:13 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}]'
2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:30:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 4)'
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
,2017-07-28 10:30:13 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":63243}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [2, 7, 10, 24]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:24
[ThaliCore] VirtualSocket.closeStreams() vsID:24
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisc,onnectHandler
,[ThaliCore] VirtualSocket.deinit vsID:24 [2, 7, 10]
,2017-07-28 10:30:13 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Advertiser: session connected Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Advertiser: session connected Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
2017-07-28 10:30:14 - DEBUG t,haliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 5)'
2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":63243}'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [2, 7, 10, 25]
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"746F6ED9-D195-4EAC-8676-23249C3D2C78","generation":0}]'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"746F6ED9-D195-4EAC-8676-23249C3D2C78","generation":0}'
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [2, 7, 10]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"746F6ED9-D195-4EAC-8676-23249C3D2C78","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:30:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"746F6ED9-D195-4EAC-8676-23249C3D2C78","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 746F6ED9-D195-4EAC-8676-23249C3D2C78 (syncValue: 6)'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-28 10:30:14 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:538E926E-B201-4924-A207-2E81E539D7B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "538E926E-B201-4924-A207-2E81E539D7B5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA","generation":0}]'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA","generation":0}'
,2017-07-28 10:30:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-28 10:30:14 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] Session.session(_:peer:didChange:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [2, 7, 10, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "746F6ED9-D195-4EAC-8676-23249C3D2C78", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63382
,2017-07-28 10:30:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":63382}'
,2017-07-28 10:30:17 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA (syncValue: 7)'
,2017-07-28 10:30:17 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0) creating a new relay
[ThaliCo,re] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[Thali,Core] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41 state: connecting -> connected
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLi,stening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:27 [2, 7, 10, 26, 27]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:28 [2, 7, 10, 26, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:27
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] VirtualSocket exited RunLoop vsID:27
[ThaliCore] VirtualSocket.deinit vsID:27 [2, 7, 10, 26, 28]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,9 [2, 7, 10, 26, 28, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [2, 7, 10, 26, 28, 29, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
[ThaliCore] VirtualSocket.deinit vsID:26 [2, 7, 10, 28, 29, 30]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [2, 7, 10, 28, 29, 30, 31]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-28 10:30:17 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [2, 7, 10, 28, 29, 30, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:33 [2, 7, 10, 28, 29, 30, 31, 32, 33]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:34 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39]
[ThaliCore] BrowserRelay,.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:37 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 40]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 40, 41]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 40, 41, 42]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:746F6ED9-D195-4EAC-8676-23249C3D2C78:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:30:18 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 40, 41, 42]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 40, 41, 42, 44]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:40
[ThaliCore] VirtualSocket.closeStreams() vsID:40
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:40
[ThaliCore] VirtualSocket.deinit vsID:40 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 42, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:42
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
[ThaliCore] VirtualSocket.deinit vsID:42 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 44]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 44, 45]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 44, 45, 46]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:45
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
[ThaliCore] VirtualSocket.deinit vsID:45 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 44, 46]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[Th,aliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4,7 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 44, 46, 47]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:46
,[ThaliCore] VirtualSocket.closeStreams() vsID:46
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:46 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 44, 47]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:44
[ThaliCore] VirtualSocket.closeStreams() vsID:44
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,44
[ThaliCore] VirtualSocket.deinit vsID:44 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 47]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError,:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:47
[ThaliCore] VirtualSocket.closeStreams() vsID:47
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
[ThaliCore] VirtualSocket.deinit vsID:47 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliC,ore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:63407
2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":null,"portNumber":63407}'
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 8)'
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":63243}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 49]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 49, 50]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 49]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:20 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Session.startOutputStream(with:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,1 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 49, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:51
[ThaliCore] VirtualSocket.deinit vsID:51 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 49]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:49
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 52]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-28 10:30:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 52, 53]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 52, 53, 54]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] Session.startOutputStream(with:) peer:C4D8EBCC-2B0A-4A94-995D-582966CD9F41
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,5 [2, 7, 10, 28, 29, 30, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 52, 53, 54, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,2017-07-28 10:30:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-28 10:30:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:33
[ThaliCore] Browse,rRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescripti,on=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCo,re] VirtualSocket.closeStreams() vsID:35
[ThaliCore] VirtualSocket exited RunLoop vsID:30
[ThaliCore] VirtualSocket.deinit vsID:30 [2, 7, 10, 28, 29, 31, 32, 33, 34, 35, 36, 38, 39, 41, 48, 52, 53, 54, 55]
[ThaliCore] TCPListener.socketDidDisconnect(_:w,ithError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed,, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:33
,[ThaliCore] VirtualSocket.deinit vsID:33 [2, 7, 10, 28, 29, 31, 32, 34, 35, 36, 38, 39, 41, 48, 52, 53, 54, 55]
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [2, 7, 10, 28, 29, 31, 32, 34, 36, 38, 39, 41, 48, 52, 53, 54, 55]
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:39
,[ThaliCore] VirtualSocket.deinit vsID:39 [2, 7, 10, 28, 29, 31, 32, 34, 36, 38, 41, 48, 52, 53, 54, 55]
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 9)'
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
,2017-07-28 10:30:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":63243}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [2, 7, 10, 28, 29, 31, 32, 34, 36, 38, 41, 48, 52, 53, 54, 55, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [2, 7, 10, 28, 29, 31, 32, 34, 36, 38, 41, 48, 52, 53, 54, 55, 56, 57]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:56
[ThaliCore] VirtualSocket.closeStreams() vsID:56
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:56
[ThaliCore] VirtualSocket.deinit vsID:56 [2, 7, 10, 28, 29, 31, 32, 34, 36, 38, 41, 48, 52, 53, 54, 55, 57]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket ,removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:20 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:29
[ThaliCore] VirtualSocket.deinit vsID:29 [2, 7, 10, 28, 31, 32, 34, 36, 38, 41, 48, 52, 53, 54, 55, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliC,ore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
[ThaliCore] VirtualSocket.deinit vsID:32 [2, 7, 10, 28, 31, 34, 36, 38, 41, 48, 52, 53, 54, 55, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore], TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:36
[ThaliCore] VirtualSocket.closeStreams() vsID:36
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
[ThaliCore] VirtualSocket.deinit vsID:36 [2, 7, 10, 28, 31, 34, 38, 41, 48, 52, 53, 54, 55, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCP,Client.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] Session.startOutputStream(with:) peer:7041977B-D95C-4E4F-A6B3-54D343A2066B
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:58 [2, 7, 10, 28, 31, 34, 38, 41, 48, 52, 53, 54, 55, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:41
[ThaliCore] VirtualSocket.closeStreams() vsID:41
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [2, 7, 10, 28, 31, 34, 38, 48, 52, 53, 54, 55, 57, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCP,Client.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [2, 7, 10, 28, 31, 34, 38, 48, 52, 53, 54, 57, 58]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8F728DD4-ACCC-4512-A3C4-EB7BD9C7C6EA:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [2, 7, 10, 28, 31, 34, 38, 48, 52, 53, 54, 57, 58, 59]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
,[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [2, 7, 10, 28, 31, 34, 38, 48, 52, 53, 54, 57, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] VirtualSocket.deinit vsID:57 [2, 7, 10, 28, 31, 34, 38, 48, 52, 53, 54, 59]
,2017-07-28 10:30:21 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Session.startOutputStream(with:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,0 [2, 7, 10, 28, 31, 34, 38, 48, 52, 53, 54, 59, 60]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=48 "Address already in use" UserInfo={NSLocalizedDescription=Address already in use, NSLocalizedFailureReason=Error in co,nnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:60
[ThaliCore] VirtualSocket.closeStreams() vsID:60
[ThaliCore] AdvertiserR,elay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:60
[ThaliCore] VirtualSocket.deinit vsID:60 [2, 7, 10, 28, 31, 34, 38, 48, 52, 53, 54, 59]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:31
[ThaliCore] VirtualSocket.closeStreams() vsID:31
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,31
[ThaliCore] VirtualSocket.deinit vsID:31 [2, 7, 10, 28, 34, 38, 48, 52, 53, 54, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnect,ed
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:34
[ThaliCore] VirtualSocket.closeStreams() vsID:34
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,34
[ThaliCore] VirtualSocket.deinit vsID:34 [2, 7, 10, 28, 38, 48, 52, 53, 54, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,38
[ThaliCore] VirtualSocket.deinit vsID:38 [2, 7, 10, 28, 48, 52, 53, 54, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[Tha,liCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:,48
[ThaliCore] VirtualSocket.deinit vsID:48 [2, 7, 10, 28, 52, 53, 54, 59]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCo,re] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-28 10:30:22 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 10)'
2017-07-28 10:30:22 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
2017-07-28 10:30:22 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"10","error":null,"portNumber":63243}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [2, 7, 10, 28, 52, 53, 54, 59, 61]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStr,eamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:61
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:61
[Th,aliCore] VirtualSocket.deinit vsID:61 [2, 7, 10, 28, 52, 53, 54, 59]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] Browse,rRelay.didSocketDisconnectHandler
2017-07-28 10:30:22 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,2017-07-28 10:30:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2017-07-28 10:30:23 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and s,o we ignored it'
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliC,ore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vsID:52
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:53
[ThaliCore] TCPLis,tener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect,(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:54
[ThaliCore] TCPListener.socketDidDi,s,connect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler ,state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler ,state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:54
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] VirtualSocket.deinit vsID:52 [2, 7, 10, 28, 53, 54, 59]
[ThaliCore] BrowserRelay.didSocketDis,connectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:59
[ThaliCore] VirtualSocket.deinit vsID:53 [2, 7, 10, 28, 54, 59]
[ThaliCore] VirtualSocket.deinit vsID:54 [2, 7,, ,10, 28, 59]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:59
[ThaliCore] VirtualSocket.deinit vsID:59 [2, 7, 10, 28]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Session.startOutputStream(with:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [2, 7, 10, 28, 62]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=36 "Operation now in progress" UserInfo={NSLocalizedDescription=Operation now in progress, NSLocalizedFailureReason=Error, in connect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:62
[ThaliCore] VirtualSocket.closeStreams() vsID:62
[ThaliCore] Adver,tiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
[ThaliCore] VirtualSocket.deinit vsID:62 [2, 7, 10, 28]
,2017-07-28 10:30:24 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 11)'
2017-07-28 10:30:24 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) found active relay
2017-07-28 10:30:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"11","error":null,"portNumber":63243}'
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:63 [2, 7, 10, 28, 63]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:63
[ThaliCore] VirtualSocket.closeStreams() vsID:63
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:63
[Th,aliCore] VirtualSocket.deinit vsID:63 [2, 7, 10, 28]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-28 10:30:24 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:63243
[ThaliCore] Session.disconnect() peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
,2017-07-28 10:30:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":"Session disconnected","portNumber":null}'
,[ThaliCore] Session.deinit peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] Session.startOutputStream(with:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6,4 [2, 7, 10, 28, 64]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:64
[ThaliCore] VirtualSocket.closeStreams() vsID:64
[ThaliCore] Advertiser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:64
[ThaliCore] VirtualSocket.deinit vsID:64 [2, 7, 10, 28]
,2017-07-28 10:30:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 0ED2C542-CB86-45A5-99D9-C349BC60F395 (syncValue: 12)'
2017-07-28 10:30:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPe,er(_:syncValue:retryCount:completion:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", g,eneration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconne,cted:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0E,D2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0A23AE11-BE34-4E78-8FF3-8598FECB3BA4 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9D650D87-8C6C-4AED-A3AE-5132A5710C9F", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:701D18EE-61FC-4884-9394-6931A9342548
,[ThaliCore] Session.deinit peer:701D18EE-61FC-4884-9394-6931A9342548
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0E,D2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0E,D2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:0ED2C542,-CB86-45A5-99D9-C349BC60F395 error: max retries exceeded
2017-07-28 10:30:40 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"12","error":"Connection could not be established","portNumber":null}'
,2017-07-28 10:30:40 - DEBUG thaliPeerPoolDefault: 'Got err   Connection could not be established'
,[ThaliCore] Session.deinit peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0ED2C542-CB86-45A5-99D9-C349BC60F395:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0ED2C542-CB86-45A5-99D9-C349BC60F395", generation: 0)
2017-07-28 10:30:41 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}]'
2017-07-28 10:30:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","generation":0}'
,2017-07-28 10:30:41 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-28 10:30:41 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"0ED2C542-CB86-45A5-99D9-C349BC60F395","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-28 10:30:41 - WARN thaliNotificationClient: 'peer is not avai,lable'
,2017-07-28 10:33:13 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-28 10:33:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:33:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:33:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4,EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:34:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:34:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:35:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:35:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:36:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:36:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:37:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:37:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4,EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:38:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:38:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:39:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:39:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4,EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-28 10:40:12 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-28 10:40:12 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-28 10:,40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-28 10:40:12 - INF,O, CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER resu,lt: passed - another'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***T,EST_LOGGER result: passed - test sinon sansbox spy'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox ,stub override'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
2017-07-28 ,1,0:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***,TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call ,start/stopListeningForAdvertisements'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: pass,ed - Calling stopListeningForAdvertisements without calling start is NOT an error'
2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
2017-07-28 10:40:12 - INFO CoordinatedCli,e,nt: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - should be able to call #stopListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can do HTTP requests between peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - can still do HTTP requests between peers with coordinator'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - calls correct starts when network changes'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test to coordinate connection cut'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests after connections are cut'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - will fail bad PSK connection between peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We provide notification when a listener dies and we recreate it'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent with the same generation and different port when listener is recreated'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start - Causing native or wifi to fail will cause a promise reject '
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #start should fail if called twice in a row'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #start subscribes to the WiFi infrastructure events and #stop unsubscribes from them (in WiFi-only mode)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not emit duplicate discoveryAdvertisingStateUpdate'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - does not send duplicate availability changes'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (native)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer added/removed to/from cache (wifi)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - new peer is cached'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with same port and different generation is cached (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with greater generation is cached (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native available - peer with same or older generation is ignored (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - new peer is ignored'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native unavailable - cached peer is removed'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for wifi peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - new peer is ignored (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (TCP_NATIVE)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort field (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - newAddressPort field (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - error when peer has not been discovered yet'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached native peer and calls `_multiConnect` to retrieve the port (MPCF)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #getPeerHostInfo - returns discovered cached wifi peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect fails on wifi peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #disconnect delegates native peers to the native wrapper'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes emitted correctly'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in started state'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - network changes not emitted in stopped state'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on Android'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We properly fire peer unavailable and then available when connection fails on iOS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - does not fire duplicate events after peer listener recreation'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #stop should change peers'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - If there are more then PEERS_LIMIT peers presented then `discoveryDOS` event should be emitted'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer should be found once after listening and discovery started'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get data from all participants'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - test for data corruption'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - test getters'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start and kill'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - double start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - start after kill'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - make sure ids are unique'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #testThaliPeerAction - check that forever agent can be destroyed'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary basic functionality'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test PeerDictionary with multiple entries.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - RESOLVED entries are removed before WAITING state entry.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - WAITING entries are removed before CONTROLLED_BY_POOL state entry.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - When CONTROLLED_BY_POOL entry is removed and kill is called.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - single action'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - multiple actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - PSK Pool works'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolDefault - stop'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that start verifies queue length'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - bad enqueues'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - do not allow same object type'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure we catch kill and dequeue'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #ThaliPeerPoolInterface - make sure that stop removes all actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized connection type'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We reject unrecognized action type'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - One action on bluetooth'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Two notification actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - replicateThroughProblems'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Replication goes first'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows many parallel non-replication actions'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - wifi allows no more than 2 simultaneous replication actions for same peerID'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Client to server request coordinated'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test BEACONS_RETRIEVED_AND_PARSED locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test HTTP_BAD_RESPONSE locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test NETWORK_PROBLEM locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails when getPeerHostInfo fails'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the start two times'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill before calling the start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill immediately after the start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Call the kill while waiting a response from the server'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test to exceed the max content size locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the server socket while the client is waiting a response from the server. Local test.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Close the client socket while the client is waiting a response from the server. Local test.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons bad args'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons empty keys to notify'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #generatePreambleAndBeacons multiple keys to notify'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid expiration in beaconStreamWithPreAmble'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons expiration out of range lower'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons no beacons returns null'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback fails decrypt'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #parseBeacons addressBookCallback returns no matches'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns spurious match'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #parseBeacons addressBookCallback returns public key'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskIdentityField'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecret'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generatePskSecrets'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - validate generateBeaconStreamAndSecrets'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Add two Peers.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP_NATIVE peer loses DNS'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Received beacons with no values for us'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Notification action killed with a superseded'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Resolves an action locally using ThaliPeerPoolDefault'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Action fails because of a bad hostname.'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - hostaddress is removed when the action is running. '
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notificationClient does not retry action with BAD_PEER resolution'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - notification client correctly handles peer availability changes of the same peer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Client to server request locally'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache clean and expiration'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache getSecret and getPublic'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Test ThaliPskMapCache multiple entries'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start and stop ThaliNotificationServer'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty array to ThaliNotificationServer.start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass a string to ThaliNotificationServer.start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Pass an empty parameter to ThaliNotificationServer.start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeacons (no keys)'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make an HTTP request to /NotificationBeaconsbefore calling start'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure peerDictionaryKey is reasonable'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure start works'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure stop works'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Emits error event when peerPool.enqueue throws'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Simple peer event'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated pull replication from notification test'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server is not there'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server accepts & closes connection'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 500'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 401'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Server always returns 403'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with same name as local db'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure docs replicate with remote db with different name than local db'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do nothing and make sure we time out'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Do something and make sure we time out'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Start replicating and then catch error when server goes'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Make sure clone works'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Coordinated replication action test - each device has the same local db name'
,2017-07-28 10:40:12 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Coordinated replication action test - each device has different local db name, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Appl,ication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxc,ore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1,
''
,2017-07-28 10:40:12 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,not ok 865 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-28 10:40:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:40:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:40:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:41:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:41:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:42:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:42:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:43:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:43:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:43:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:43:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-28 10:43:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA,0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-28 10:43:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/0D340B2A-941F-4EA0-A056-9822335D8140/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
