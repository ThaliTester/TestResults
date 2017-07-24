#### Test 12719871034799d6_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/12719871034799d6/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/9F8BD3D9-3E23-419F-8D84-C71146F343D4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/9F8BD3D9-3E23-419F-8D84-C71146F343D4/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/12719871034799d6/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/12719871034799d6/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:53851"
,(lldb)     command script import "/tmp/9F8BD3D9-3E23-419F-8D84-C71146F343D4/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,JXcore engine is started
,2017-07-24 11:01:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:01:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:01:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:01:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:01:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:01:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:01:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "29F15FDB-A595-4C07-9C6E-EC4889BCF298", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:29F15FDB-A595-4C07-9C6E-EC4889BCF298
Optional(tru,e)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:72C62BCF-91A4-49FE-B4D0-4E6C07E2F6E6
[ThaliCore] Browser,.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:953BBBFD-,38BC-492A-BB4E-7BAC9E355666
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E807A603-BD96-4B93-9384-FA9AE892ECA0", generation: 0)
[ThaliCore] Advertiser.startAdvertisi,ng with peerID:E807A603-BD96-4B93-9384-FA9AE892ECA0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E807A603-BD96-4B93-9384-FA9AE892ECA0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E807A603-BD96-4B93-9384-FA9AE892ECA0", generation: 0)
AppContextTests.test_startAdv,ertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTes,ts finished
All tests finished
All tests finished
,2017-07-24 11:01:14 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.536284029483795
,2017-07-24 11:01:14 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-07-24 11:01:14 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E807A603-BD96-4B93-9384-FA9AE892ECA0:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E807A603-BD96-4B93-9384-FA9AE892ECA0", generation: 0)
,2017-07-24 11:01:17 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-24 11:01:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-24 11:01:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-24 11:01:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-24 11:01:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-24 11:01:17 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-24 11:01:18 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-24 11:01:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-24 11:01:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-24 11:01:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-24 11:01:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-24 11:01:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-24 11:01:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-24 11:01:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-24 11:01:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-24 11:01:19 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-24 11:01:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-24 11:01:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-24 11:01:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-24 11:01:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-24 11:01:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-24 11:01:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-24 11:01:21 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-24 11:01:21 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-24 11:01:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:01:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:01:57 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-07-24 11:01:57 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-24 11:01:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-24 11:02:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-24 11:02:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 3 Got the right error
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
ok 6 should be equal
,# teardown
,# setup
,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
,ok 13 should be equal
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
,ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
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
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:72A05D44-65FC-4B1B-A93B-8D9CFFFF4719
,[ThaliCore] Browser.startListening
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:20FAA4DD-E6D4-4597-9B74-0A441F7F89EA
[ThaliCore] Browser.startListening
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:02:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24, 11:02:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",networkType":null}})'
2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:02:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:02:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
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
,2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:25 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "899672CF-6975-4C3C-A89F-DD2F001BA0C5", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:899672CF-6975-4C3C-A89F-DD2F001BA0C5
2017-07-24 1,1:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 68 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:899672CF-6975-4C3C-A89F-DD2F001BA0C5
2017-07-24 11:02:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
,2017-07-24 11:02:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Can call stopAdvertisingAndListening without error
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "1C129043-3552-4C65-9BD4-65B9189D7494", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:1C129043-3552-4C65-9BD4-65B9189D7494
2017-07-24 11:02:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:27, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-24 11:02:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(,onPort:errorHandler:) Peer(uuid: "1C129043-3552-4C65-9BD4-65B9189D7494", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:1C129043-3552-4C65-9BD4-65B9189D7494
2017-07-24 11:02:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingS,t,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:02:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:1C129043-3552-4C65-9BD4-65B9189D7494
[ThaliCore] Advertiser.stopAdvertising() peerID:1C129043-3552-4C65-9BD4-65B9189D7494,
2017-07-24 11:02:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:02:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state,).'
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
,ok 73 Can call stopAdvertisingAndListening without error
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9699B0E1-44B9-482F-A4AC-FD3E9344992A", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9699B0E1-44B9-482F-A4AC-FD3E9344992A
2017-07-24 1,1:02:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4D6F1229-6C66-49C9-8D72-D0A6A88DEE59
[Thali,Core] Browser.startListening
,2017-07-24 11:02:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:02:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:02:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A8BB093A-4D70-46E4-9D84-4E14AF3D9C9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A8BB093A-4D70-46E4-9D84-4E14AF3D9C9B", generation: 0)
ok 76 peers must be an array,
ok 77 peers must not be zero-length
ok 78 peer must have only peerIdentifier, peerAvailable and generation properties
ok 79 peerIdentifier must be a string
ok 80 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9699B0E1-44B9-482F-A4AC-FD3E9344992A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9699B0E1-44B9-482F-A4AC-FD3E9344992A", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:489BD2DA-ED40-4C42-A931-8C514A214BF5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "489BD2DA-ED40-4C42-A931-8C514A214BF5", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:02:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9699B0E1-44B9-482F-A4AC-FD3E9344992A
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "381B7A74-7122-4015-A89E-4B737500991B", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:381B7A74-7122-4015-A89E-4B737500991B
2017-07-24 1,1:02:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 81 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9437DC0E-0407-4771-AF4C-DA9C3D8A287D
[Thal,i,Core] Browser.startListening
2017-07-24 11:02:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:02:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:35 - INFO thaliMobile: 'Filtere,d out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
2017-07-24 11:02:36 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"01BFBF0D-498C-4989-932F-2BFF5B82FD2A","generation":0}'
2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 01BFBF0D-498C-4989-932F-2BFF5B82FD2A, (syncValue: TL09SwnygcF9HVfkPoGJHUUL3spq8wOy)'
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD1166F3-65E0-4A9D-9015-16F0811DA565:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD1166F3-65E0-4A9D-9015-16F0811DA565", generation: 0)
[ThaliCore] Session.session(_,:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: notConnected -> connecting
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD1166F3-65E0-4A9D-9015-16F0811DA565","generation":0}'
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:02:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:381B7A74-7122-4015-A89E-4B737500991B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "381B7A74-7122-4015-A89E-4B737500991B", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60388
,2017-07-24 11:02:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"TL09SwnygcF9HVfkPoGJHUUL3spq8wOy","error":null,"portNumber":60388}'
,2017-07-24 11:02:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'TL09SwnygcF9HVfkPoGJHUUL3spq8wOy', error: 'null', listeningPort: '60388''
,2017-07-24 11:02:38 - INFO testThaliMobileNative: ''
,ok 83 Must have listeningPort
,ok 84 listeningPort must be a number
,ok 85 listening port should not be 0
,# teardown
,2017-07-24 11:02:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,11:02:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 11:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:381B7A74-7122-4015-A89E-4B737500991B
2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"a,dvertisingActive":false}'
2017-07-24 11:02:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60388
[ThaliCore] Session.disconnect() peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5ACAF211-0772-4AB0-B392-E6D7695E2A89
2017-07-24 1,1:02:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:9942A511-D408-413D-BEDD-B792FE6F9E6D
[Thal,iCore] Browser.startListening
2017-07-24 11:02:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:02:44 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"01BFBF0D-498C-4989-932F-2BFF5B82FD2A","generation":0}'
,2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 01BFBF0D-498C-4989-932F-2BFF5B82FD2A (syncValue: fkDKI8AusoDhjVAWffAsm5GR2s7HhMKz)'
,2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
2017-07-24 11:02:45 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6","generation":0}'
2017-07-24 11:02:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:02:45 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
2017-07-24 11:02:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E2A40D56-96CA-4D8D-8F53-D4CC01876154","generation":0}'
2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:02:46 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-24 11:02:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5ACAF211-0772-4AB0-B392-E6D7695E2A89:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5ACAF211-0772-4AB0-B392-E6D7695E2A89", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:01,BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
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
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,1BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:01,BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,1BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "01BFBF0D-498C-4989-932F-2BFF5B82FD2A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:02:53 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fkDKI8AusoDhjVAWffAsm5GR2s7HhMKz","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:02:53 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'fkDKI8AusoDhjVAWffAsm5GR2s7HhMKz', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 11:02:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"01BFBF0D-498C-4989-932F-2BFF5B82FD2A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:02:53 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-24 11:02:53 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"01BFBF0D-498C-4989-932F-2BFF5B82FD2,A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:02:53 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:02:53 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 11:02:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6 (syncValue: XQyGRaGZ43vtKeTGE5xgsMV,uqytJ0WAx)'
2017-07-24 11:02:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BD9F2C7A-F67B-4FF6-92A5-D205E,FC2A0B6:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-24 11:02:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:01BFBF0D-498C-4989-932F-2BFF5B82FD2A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60394
,2017-07-24 11:02:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XQyGRaGZ43vtKeTGE5xgsMVuqytJ0WAx","error":null,"portNumber":60394}'
,2017-07-24 11:02:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XQyGRaGZ43vtKeTGE5xgsMVuqytJ0WAx', error: 'null', listeningPort: '60394''
,Connecting to the localhost:60394
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
Connected to the localhost:60394
,2017-07-24 11:02:56 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 11:02:56 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 88 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
,[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,2017-07-24 11:02:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:5ACAF211-0772-4AB0-B392-E6D7695E2A89
2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11,:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListen,er.stopListeningForConnectionsAndDisconnectClients() port:60394
[ThaliCore] Session.disconnect() peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.dei,nit
,[ThaliCore] Session.deinit peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:B7A64547-3C92-4AEA-B913-F34E280DDD7C
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:02:59 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 89 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7FED5B98-CE04-4E64-9EB3-69D2831659CA
[ThaliCore] Browser.startListening
,2017-07-24 11:02:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:02:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 11:02:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
2017-07-24 11:03:00 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E2A40D56-96CA-4D8D-8F53-D4CC01876154","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E2A40D56-96CA-4D8D-8F53-D4CC01876154 (syncValue: kzheXMXNk2jg05QuZY8OIsHiY3T8gcxW)'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6","generation":0}'
2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BD9F2C7A-F67B-4FF6-92A5-D205EFC2A0B6", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:B7A64547-3C92-4AEA-B913-F34E280DDD7C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8DB5C8CF-9F6C-4FCE-AE67-31A370211A57","generation":0}'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:00 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E2,A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E2A40D56-96CA-4D8D-8F53-D4CC01876154", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:03:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kzheXMXNk2jg05QuZY8OIsHiY3T8gcxW","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:03:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kzheXMXNk2jg05QuZY8OIsHiY3T8gcxW', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:03:05 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"E2A40D56-96CA-4D8D-8F53-D4CC01876154","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 11:03:05 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E2A40D56-96CA-4D8D-8F53-D4CC01876154","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-24 11:03:05 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:05 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 11:03:05 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3 (syncValue: ajCIwiqozfbizXIwqCoAqYD,LPxJKl7W9)'
2017-07-24 11:03:05 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:15F8FDF1-E29F-4B1B-AFBA-A337E,CE93BE3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:03:05 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E2A40D56-96CA-4D8D-8F53-D4CC01876154:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60406
,2017-07-24 11:03:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ajCIwiqozfbizXIwqCoAqYDLPxJKl7W9","error":null,"portNumber":60406}'
,2017-07-24 11:03:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ajCIwiqozfbizXIwqCoAqYDLPxJKl7W9', error: 'null', listeningPort: '60406''
,Connecting to the localhost:60406
,Connecting to the localhost:60406
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
Connecting to the local,host:60406
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
Connected to the localhost:60406
,Connected to the localhost:60406
,Connected to the localhost:60406
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 91 correct string length
,2017-07-24 11:03:08 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 92 correct string length
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 93 correct string length
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-24 11:03:09 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vs,ID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [2, 4]
,ok 94 got the same data back
,ok 95 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 96 got the same data back
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC
[ThaliCore] Advertiser: session connected Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E5908147-7A14-434D-B742-7872530D4239
[ThaliCore] Advertiser: session connected Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E5908147-7A14-434D-B742-7872530D4239 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC
,[ThaliCore] Session.session(_:peer:didChange:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC
[ThaliCore] Session.startOutputStream(with:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [2, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC
[ThaliCore] Session.startOutputStream(with:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 4, 5, 6]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC
[ThaliCore] Session.startOutputStream(with:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7, [2, 4, 5, 6, 7]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received (4096 bytes):'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received (5120 bytes):'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received (4978 bytes):'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received (4380 bytes):'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received (3072 bytes):'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received (5688 bytes):'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received (3244 bytes):'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 11:03:15 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:6
,[ThaliCore] VirtualSocket.closeStreams() vsID:5
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
,[ThaliCore] VirtualSocket.deinit vsID:5 [2, 4, 6, 7]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:6 [2, 4, 7]
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (13099 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:7
,[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [2, 4]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E5908147-7A14-434D-B742-7872530D4239
,[ThaliCore] Session.session(_:peer:didChange:) peer:E5908147-7A14-434D-B742-7872530D4239 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E5908147-7A14-434D-B742-7872530D4239
[ThaliCore] Session.startOutputStream(with:) peer:E5908147-7A14-434D-B742-7872530D4239
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 4, 8]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E5908147-7A14-434D-B742-7872530D4239
[ThaliCore] Session.startOutputStream(with:) peer:E5908147-7A14-434D-B742-7872530D4239
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9, [2, 4, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E5908147-7A14-434D-B742-7872530D4239
[ThaliCore] Session.startOutputStream(with:) peer:E5908147-7A14-434D-B742-7872530D4239
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [2, 4, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received all data: 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'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:8
,[ThaliCore] VirtualSocket.deinit vsID:8 [2, 4, 9, 10]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (6529 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
,[ThaliCore] VirtualSocket.deinit vsID:9 [2, 4, 10]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-24 11:03:16 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
,[ThaliCore] VirtualSocket.deinit vsID:10 [2, 4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocke,tDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:E5908147-7A14-434D-B742-7872530D4239 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:E5908147-7A14-434D-B742-7872530D4239
[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 11:03:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [2]
2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:0,3:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:03:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:B7A64547-3C92-4AEA-B913-F34E280DDD7C
,2017-07-24 11:03:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60406
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:6A1E10F6-FE19-4661-9EC8-B943F58198BC state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "B7A64547-3C92-4AEA-B913-F34E280DDD7C", generation: 0)
,[ThaliCore] Session.deinit peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
[ThaliCore] Session.deinit peer:E5908147-7A14-434D-B742-7872530D4239
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:2BDCF5F5-8C04-4171-800A-A898BAF20B04
,2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:03:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 97 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B2076B65-0D70-4CE7-A471-5FDF34A76145
[ThaliCore] Browser.startListening
2017-07-24 11:03:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:03:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 11:03:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
2017-07-24 11:03:18 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8DB5C8CF-9F6C-4FCE-AE67-31A370211A57","generation":0}'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8DB5C8CF-9F6C-4FCE-AE67-31A370211A57, (syncValue: BPwAwsLBZCkUPu6SPQMRaw09GNEiQUjT)'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3","generation":0}'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ADD0124E-485B-4CBD-9E05-99F82050A2E9","generation":0}'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F591386-896D-46D9-B7FC-0F4D50F2F645","generation":0}'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:18 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2BDCF5F5-8C04-4171-800A-A898BAF20B04:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8D,B5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8D,B5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:8D,B5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8,DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8DB5C8CF-9F6C-4FCE-AE67-31A370211A57", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"BPwAwsLBZCkUPu6SPQMRaw09GNEiQUjT","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:03:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'BPwAwsLBZCkUPu6SPQMRaw09GNEiQUjT', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"8DB5C8CF-9F6C-4FCE-AE67-31A370211A57","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8DB5C8CF-9F6C-4FCE-AE67-31A370211A57","peerAvailable":true,"portNumber":null,"recreated,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E3D28789-D0C6-46FF-A0DF-99E9B76A37A5
[ThaliCore] Advertiser: session connected Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:E3D28789-D0C6-46FF-A0DF-99E9B76A37A5 state: notConnected -> connecting
":true}'
,2017-07-24 11:03:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:8DB5C8CF-9F6C-4FCE-AE67-31A370211A57:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:03:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 11:03:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3 (syncValue: oApVW6Zg73Y3QNryhUYiCBMjiyH4XI5F)'
,2017-07-24 11:03:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:03:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:26 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:E3D28789-D0C6-46FF-A0DF-99E9B76A37A5
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2
[ThaliCore] Advertiser: session connected Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:15,F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oApVW6Zg73Y3QNryhUYiCBMjiyH4XI5F","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'oApVW6Zg73Y3QNryhUYiCBMjiyH4XI5F', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3","peerAvailable":true,"portNumber":null,"recreated,":true}'
,2017-07-24 11:03:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for ADD0124E-485B-4CBD-9E05-99F82050A2E9 (syncValue: vgyT4ebumoonfYB1bkf5f33IEggU4zvF)'
2017-07-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:03:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:15F8FDF1-E29F-4B1B-AFBA-A337ECE93BE3:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3D28789-D0C6-46FF-A0DF-99E9B76A37A5 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:E3D28789-D0C6-46FF-A0DF-99E9B76A37A5
[ThaliCore] Session.startOutputStream(with:) peer:E3D28789-D0C6-46FF-A0DF-99E9B76A37A5
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [2, 11]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-24 11:03:29 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 11:03:29 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 11:03:29 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-24 11:03:29 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 11:03:29 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [2]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2
,[ThaliCore] Session.session(_:peer:didChange:) peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2
[ThaliCore] Session.startOutputStream(with:) peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [2, 12]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,Server received psk id: psk-id
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes): '
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Server's socket stream finished'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:12
,[ThaliCore] VirtualSocket.deinit vsID:12 [2]
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60432
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vgyT4ebumoonfYB1bkf5f33IEggU4zvF","error":null,"portNumber":60432}'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vgyT4ebumoonfYB1bkf5f33IEggU4zvF', error: 'null', listeningPort: '60432''
,Connecting to the localhost:60432
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [2, 13]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:60432
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-24 11:03:32 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 99 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:13
,# teardown
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:13
[ThaliCore] VirtualSocket.deinit vsID:13 [2]
,2017-07-24 11:03:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:03:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:03:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:2BDCF5F5-8C04-4171-800A-A898BAF20B04
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,[ThaliCore] BrowserManager.disconnect peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60432
[ThaliCore] Session.disconnect() p,eer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2
,[ThaliCore] Session.deinit peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E3D28789-D0C6-46FF-A0DF-99E9B76A37A5 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "2BDCF5F5-8C04-4171-800A-A898BAF20B04", generation: 0)
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] Session.deinit peer:4BE7335F-67BD-401E-B0C7-2C7A07B5ECA2
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:12089FF0-3ECC-40A2-A184-6C264C0E4B6C
,2017-07-24 11:03:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:03:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:03:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:26A39883-A498-46D9-BCE1-537D2CD964F5
,[ThaliCore] Browser.startListening
,2017-07-24 11:03:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:03:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 11:03:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
2017-07-24 11:03:34 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3F591386-896D-46D9-B7FC-0F4D50F2F645","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3F591386-896D-46D9-B7FC-0F4D50F2F645 (syncValue: CM8GQz2KetZ3eKCQEx7OSM5FSygZXH1D)'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5,-B8AE-21666B67C798:0
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
[ThaliCore] BrowserManager.conn,ectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F,645", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketD,isconnected:stoppedListening:)
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"ADD0124E-485B-4CBD-9E05-99F82050A2E9","generation":0}'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}'
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12089FF0-3ECC-40A2-A184-6C264C0E4B6C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12089FF0-3ECC-40A2-A184-6C264C0E4B6C", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FA2EE142-1A99-4149-AB82-FAA6044948AC","generation":0}'
2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:34 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:ADD0124E-485B-4CBD-9E05-99F82050A2E9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "ADD0124E-485B-4CBD-9E05-99F82050A2E9", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3F,591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:3F591386,-896D-46D9-B7FC-0F4D50F2F645 error: max retries exceeded
2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"CM8GQz2KetZ3eKCQEx7OSM5FSygZXH1D","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'CM8GQz2KetZ3eKCQEx7OSM5FSygZXH1D', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F591386-896D-46D9-B7FC-0F4D50F2F645","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3F591386-896D-46D9-B7FC-0F4D50F2F645","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F4F5F622-E47B-4CE5-B8AE-21666B67C798 (syncValue: dI2XOo5vIggP5Mo5Y2qPLBAdyCrMIlMl)'
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:03:45 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3F591386-896D-46D9-B7FC-0F4D50F2F645:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3F591386-896D-46D9-B7FC-0F4D50F2F645", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60448
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"dI2XOo5vIggP5Mo5Y2qPLBAdyCrMIlMl","error":null,"portNumber":60448}'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'dI2XOo5vIggP5Mo5Y2qPLBAdyCrMIlMl', error: 'null', listeningPort: '60448''
,Connecting to the localhost:60448
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
,Connected to the localhost:60448
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [2, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-24 11:03:48 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 102 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:14
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:14
,[ThaliCore] VirtualSocket.deinit vsID:14 [2]
,# teardown
,2017-07-24 11:03:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:03:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:12089FF0-3ECC-40A2-A184-6C264C0E4B6C
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60448
[ThaliCore] Session.disconnect() p,eer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CC3CBC64-F0A5-4277-B521-89B3C2766BA4
[ThaliCore] Browser.startListening
2017-07-24 11:03:49 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:03:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:03:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 We should start listening fine
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:,errorHandler:) Peer(uuid: "5F3344D9-A0D8-45F0-B5ED-690876F8EF43", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5F3344D9-A0D8-45F0-B5ED-690876F8EF43
2017-07-24 11:03:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpda,teNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:03:49 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"net,workType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:03:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 104 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FA2EE142-1A99-4149-AB82-FAA6044948AC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FA2EE142-1A99-4149-AB82-FAA6044948AC", generation: 0)
2017-07-24 11:03:50 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"FA2EE142-1A99-4149-AB82-FAA6044948AC","generation":0}]'
2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"FA2EE142-1A99-4149-AB82-FAA6044948AC","generation":0}'
2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}]'
,2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}'
,2017-07-24 11:03:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BD9D579D-72C6-46B0-B79B-4E6BA3F58861:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BD9D579D-72C6-46B0-B79B-4E6BA3F58861", generation: 0)
2017-07-24 11:03:51 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BD9D579D-72C6-46B0-B79B-4E6BA3F58861","generation":0}]'
2017-07-24 11:03:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BD9D579D-72C6-46B0-B79B-4E6BA3F58861","generation":0}'
2017-07-24 11:03:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5F3344D9-A0D8-45F0-B5ED-690876F8EF43:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5F3344D9-A0D8-45F0-B5ED-690876F8EF43", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 ,11:03:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:5F3344D9-A0D8-45F0-B5ED-6,90876F8EF43
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in ,s,topped state).'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
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
2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:DEEBD910-E8D1-4551-9992-FDB59DB1DB94
[ThaliCore] Browser.startListening
ok 105 discoveryActive should be false
ok 106 advertisingActive should be true
[ThaliCore] AdvertiserManager.startUpd,ateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "08A5D7F5-B0A2-40F7-83DD-8332FA0AA5F8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:08A5D7F5-B0A2-40F7-83DD-8332FA0AA5F8
ok 107 discoveryActive should be false
ok 108 adv,ertisingActive should be true
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 109 discoveryActive should be false
,ok 110 advertisingActive should be true
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:08A5D7F5-B0A2-40F7-83DD-8332FA0AA5F8
ok 111 discoveryActive should be false
ok 112 advertisingActive should be true
ok 113 Can call startListeningForAdvertisements without error
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
2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 118 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 119 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-24 11:03:57 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-24 11:03:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 121 Should be able to call stopAdvertisingAndListening in teardown
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
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:5ec655e1-248a-4d4d-8353-c94f018e6d65 error: startListeningNotActive
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"VTcH4Wv1wG9vCjTMRY67EguFf4PXEtk3","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 127 Should only get called after multiConnect returned
ok 128 SyncValue matches
ok 129 Got right error
ok 130 listeningPort is null
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5ec655e1-248a-4d4d-8353-c94f018e6d65","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5ec655e1-248a-4d4d-8353-c94f018e6d65","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpd,ateNonTCP registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:58 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5020DCDD-FFFD-4A05-9F86-F4DDCE6FAFC5
,[ThaliCore] Browser.startListening
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
2017-07-24 11:03:59 - INFO th,aliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}},)'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 No error on starting
,ok 132 Got null as expected
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"RyVayxGdd1gcEqIZvPYSL4RDZNSAKBZf","error":"Illegal peerID","portNumber":null}'
,ok 133 Should only get called after multiConnect returned
,ok 134 SyncValue matches
,ok 135 Got right error
,ok 136 listeningPort is null
,# teardown
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}]'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:03:59 - DEBUG t,haliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C0ED159A-517F-4F64-9094-31458DDCEFFA
,[ThaliCore] Browser.startListening
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:03:59 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 137 No error on starting
,ok 138 Got right error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,# teardown
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}]'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}'
,2017-07-24 11:03:59 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
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
2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:c2579acc-9004-42ac-b26b-a5f53915ba79
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
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1
,2017-07-24 11:04:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:04:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:04:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 141 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:E33259C0-2629-46E0-8125-B38346AD8EDE
,[ThaliCore] Browser.startListening
,2017-07-24 11:04:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:04:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:04:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
2017-07-24 11:04:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","generation":0}'
,2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F4F5F622-E47B-4CE5-B8AE-21666B67C798 (syncValue: pE2TvmpQPgxvjs1R97fajrlmjmC1DwMj)'
,2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
2017-07-24 11:04:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5837337D-36B1-4BEE-A7F0-8A59B6E8E759","generation":0}'
2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:02 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:63BAE976-BEB5-4F9C-9652-5FC045F4AD23:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "63BAE976-BEB5-4F9C-9652-5FC045F4AD23", generation: 0)
2017-07-24 11:04:02 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"63BAE976-BEB5-4F9C-9652-5FC045F4AD23","generation":0}'
2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
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
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:F4,F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "F,4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F4F5F622-E47B-4CE5-B8AE-21666B67C798", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:69714A12-7853-4890-86EC-F14734D64C88
[ThaliCore] Advertiser: session connected Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:69714A12-7853-4890-86EC-F14734D64C88 state: notConnected -> connecting
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 11:04:07 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"pE2TvmpQPgxvjs1R97fajrlmjmC1DwMj","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 11:04:07 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'pE2TvmpQPgxvjs1R97fajrlmjmC1DwMj', error: 'Peer is unavailable', listeningPort: '%s''
,2017-07-24 11:04:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:07 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F4F5F622-E47B-4CE5-B8AE-21666B67C798","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:07 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:07 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 11:04:07 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5837337D-36B1-4BEE-A7F0-8A59B6E8E759 (syncValue: SRB6RvXm2rhSISt19spTiqNyW8Aqa8OF)'
,2017-07-24 11:04:07 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:04:07 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:F4F5F622-E47B-4CE5-B8AE-21666B67C798:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:69714A12-7853-4890-86EC-F14734D64C88
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:69714A12-7853-4890-86EC-F14734D64C88 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60460
,2017-07-24 11:04:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SRB6RvXm2rhSISt19spTiqNyW8Aqa8OF","error":null,"portNumber":60460}'
,2017-07-24 11:04:11 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'SRB6RvXm2rhSISt19spTiqNyW8Aqa8OF', error: 'null', listeningPort: '60460''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
,ok 143 Got null as expected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:69714A12-7853-4890-86EC-F14734D64C88
[ThaliCore] Session.startOutputStream(with:) peer:69714A12-7853-4890-86EC-F14734D64C88
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:,completion:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) found active relay
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [2, 15]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,2017-07-24 11:04:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lHgEcRZ2B0kDpkypqN9O7avGZck7ldws","error":null,"portNumber":60460}'
,ok 144 No error
ok 145 Ports equal
,ok 146 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) found active relay
2017-07-24 11:04:11 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"fXi2zp4HEgSe1NS1yar75Fxo1FmQHX0a","error":null,"portNumber":60460}'
,ok 147 No error
,ok 148 Ports equal
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [2, 15, 16]
[ThaliCore] TCPClient: didConnectToHost, active con,nections count: 0
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,# teardown
,2017-07-24 11:04:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdverti,sing()
[ThaliCore] Advertiser.stopAdvertising() peerID:6C923BA5-B7BD-4950-A19A-1BFD7C7541D1
2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11,:04:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:15
[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] BrowserManager.disconnect peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60460
[ThaliCore] VirtualSocket.closeStr,eams() vsID:16
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[T,haliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] VirtualSocket.deinit vsID:15 [2, 16]
[ThaliCore] BrowserR,elay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] Session.disconnect() peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] VirtualSocket.closeStreams() vsID:16
[ThaliCore] Brow,serRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:16 [2]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.deinit
2017-07,-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:69714A12-7853-4890-86EC-F14734D64C88 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "6C923BA5-B7BD-4950-A19A-1BFD7C7541D1", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:69714A12-7853-4890-86EC-F14734D64C88
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:69714A12-7853-4890-86EC-F14734D64C88
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
2017-07-24 11:04:29 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
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
2017-07-24 11:04:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'listening 60464'
,ok 149 Should throw
,# teardown
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'listening 60466'
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
,2017-07-24 11:04:31 - DEBUG createNativeListener: 'listening 60469'
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
2017-07-24 11:04:32 - DEBUG createNativeListener: 'listening 60473'
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
2017-07-24 11:04:32 - DEBUG createNativeListener: 'listening 60478'
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
2017-07-24 11:04:33 - DEBUG createNativeListener: 'listening 60482'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 162 we should not have gotten an error
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 163 socket shouldn't close until after incoming
,ok 164 incoming is cleaned up
,# teardown
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'listening 60486'
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
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'listening 60490'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
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
,2017-07-24 11:04:34 - DEBUG createNativeListener: 'listening 60494'
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
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'listening 60546'
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 179 we should not have gotten an error
,2017-07-24 11:04:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
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
,2017-07-24 11:04:36 - DEBUG createNativeListener: 'listening 60550'
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
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'listening 60553'
ok 196 port must be in range
,# teardown
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'listening 60554'
,ok 197 second start should return same port
,# teardown
,2017-07-24 11:04:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-24 11:04:37 - DEBUG createNativeListener: 'listening 60556'
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
,listening on 60558
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
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 208 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6CAFC199-E1A2-42A9-8EB7-983A183E08B1
[ThaliCore] Browser.startListening
,2017-07-24 11:04:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:04:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 11:04:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 209 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:63BAE976-BEB5-4F9C-9652-5FC045F4AD23:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "63BAE976-BEB5-4F9C-9652-5FC045F4AD23", generation: 0)
2017-07-24 11:04:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5837337D-36B1-4BEE-A7F0-8A59B6E8E759","generation":0}'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 5837337D-36B1-4BEE-A7F0-8A59B6E8E759 (syncValue: gzf3yNwPsdwW9HO3XRKrmUI99r2xLvVA)'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"63BAE976-BEB5-4F9C-9652-5FC045F4AD23","generation":0}'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
2017-07-24 11:04:39 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"750E6DFD-0414-4611-9C4A-7D7FD6C84C77","generation":0}'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","generation":0}'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:39 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58,37337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:63BAE976-BEB5-4F9C-9652-5FC045F4AD23:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "63BAE976-BEB5-4F9C-9652-5FC045F4AD23", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58,37337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] Session.deinit peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58,37337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "5837337D-36B1-4BEE-A7F0-8A59B6E8E759", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:04:47 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"gzf3yNwPsdwW9HO3XRKrmUI99r2xLvVA","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:04:47 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'gzf3yNwPsdwW9HO3XRKrmUI99r2xLvVA', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:04:47 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"5837337D-36B1-4BEE-A7F0-8A59B6E8E759","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:04:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 11:04:47 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"5837337D-36B1-4BEE-A7F0-8A59B6E8E759","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-24 11:04:47 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:47 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 11:04:47 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 750E6DFD-0414-4611-9C4A-7D7FD6C84C77 (syncValue: EWfgr0JchrMOxCgYfUItLsk,W5D9CQyT7)'
2017-07-24 11:04:47 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:750E6DFD-0414-4611-9C4A-7D7FD,6C84C77:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:04:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:5837337D-36B1-4BEE-A7F0-8A59B6E8E759:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4
[ThaliCore] Advertiser: session connected Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4 state: connecting -> connected
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4
[ThaliCore] Advertiser:, session connected Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:48EDAA19-7445-4E6B,-ABBA-BC18A1C615E4 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60570
,2017-07-24 11:04:52 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"EWfgr0JchrMOxCgYfUItLskW5D9CQyT7","error":null,"portNumber":60570}'
,2017-07-24 11:04:52 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'EWfgr0JchrMOxCgYfUItLskW5D9CQyT7', error: 'null', listeningPort: '60570''
,ok 210 should be equal
,2017-07-24 11:04:52 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 91033B82-7A22-4EE1-8C6F-0D07A8443692 (syncValue: 1tPX1kztawkeS9nxXkZDf1sjueJXqdgn)'
2017-07-24 11:04:52 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[T,haliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9103,3B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] ,TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4
,[ThaliCore] Session.session(_:peer:didChange:) peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60574
,2017-07-24 11:04:55 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1tPX1kztawkeS9nxXkZDf1sjueJXqdgn","error":null,"portNumber":60574}'
,2017-07-24 11:04:55 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1tPX1kztawkeS9nxXkZDf1sjueJXqdgn', error: 'null', listeningPort: '60574''
,ok 211 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:04:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E
2017-07-24 11:04:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:04:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77,
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60570
[ThaliCore] Session.disconnect() peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] TCPListener.socketDidDis,connect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:B7A84CB4-CC35-4B07-B7B5-5679415DB7A4 state: connected -> notConnected
,[ThaliCore] Advertiser: session notConnected Peer(uuid: "9ECDB81E-7A35-4DA6-9B91-7CA4FB2D6B9E", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
,[ThaliCore] Session.disconnect() peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4
,[ThaliCore] Session.deinit peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:91033B82-7A22-4EE1-8C6F-0D07A8443692
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60574
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uui,d: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
,2017-07-24 11:04:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,[ThaliCore] Session.deinit peer:48EDAA19-7445-4E6B-ABBA-BC18A1C615E4
,[ThaliCore] AdvertiserRelay.deinit
,2017-07-24 11:04:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1tPX1kztawkeS9nxXkZDf1sjueJXqdgn","error":"Session disconnected","portNumber":null}'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.deinit
,# Multiple local http requests
,listening on 60576
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
,2017-07-24 11:04:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:04:57 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:D2BCE3C4-528F-472A-A98F-01BEF298D54C
2017-07-24 1,1:04:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:04:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:04:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 215 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:525D63C1-5EA0-4F7D-8705-89ECFC695D33
[Thal,iCore] Browser.startListening
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:04:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:04:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 216 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
2017-07-24 11:04:57 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","generation":0}'
2017-07-24 11:04:57 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 91033B82-7A22-4EE1-8C6F-0D07A8443692, (syncValue: 4r3Aw6eoj1G0YkXkWqypqLvb5jbzDwQq)'
2017-07-24 11:04:57 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A84,43692", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.init(s,ession:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
2017-07-24 11:04:57, - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"750E6DFD-0414-4611-9C4A-7D7FD6C84C77","generation":0}'
,2017-07-24 11:04:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:57 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
2017-07-24 11:04:58 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:04:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D2BCE3C4-528F-472A-A98F-01BEF298D54C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,1033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,1033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "9,1033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:91,033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:91033B82,-7A22-4EE1-8C6F-0D07A8443692 error: max retries exceeded
2017-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4r3Aw6eoj1G0YkXkWqypqLvb5jbzDwQq","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '4r3Aw6eoj1G0YkXkWqypqLvb5jbzDwQq', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent, due to not being in started state'
2017-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"91033B82-7A22-4EE1-8C6F-0D07A8443692","peerAvailable":true,"portNumber":null,"recreated":true}'
20,17-07-24 11:05:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:05:08 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 750E6DFD-0414-4611-9C4A-7D7FD6C84C77 (syncValue: jH0HNTs,guByl9ieFA02Jowa3qmnzOXzY)'
2017-07-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:750E6DFD-0414,-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-24 11:05:08 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015
[ThaliCore] Advertiser: session connected Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7
[ThaliCore] Advertiser: session connected Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:91033B82-7A22-4EE1-8C6F-0D07A8443692:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "91033B82-7A22-4EE1-8C6F-0D07A8443692", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7
,[ThaliCore] Session.session(_:peer:didChange:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:75,0E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,50E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:75,0E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,50E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:75,0E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "7,50E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "750E6DFD-0414-4611-9C4A-7D7FD6C84C77", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:05:16 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jH0HNTsguByl9ieFA02Jowa3qmnzOXzY","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:05:16 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jH0HNTsguByl9ieFA02Jowa3qmnzOXzY', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:05:16 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"750E6DFD-0414-4611-9C4A-7D7FD6C84C77","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:05:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-24 11:05:16 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"750E6DFD-0414-4611-9C4A-7D7FD6C84C77","peerAvailable":true,"portNumber":null,"recreate,d":true}'
2017-07-24 11:05:16 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-24 11:05:16 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-24 11:05:16 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C1DE2F08-A697-4531-80C7-AC50F60F4088 (syncValue: 79rJgsOSRxNUwP64X7s521K,RLG9BEjpC)'
2017-07-24 11:05:16 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C1DE2F08-A697-4531-80C7-AC50F,60F4088:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:05:16 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:750E6DFD-0414-4611-9C4A-7D7FD6C84C77:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60600
,2017-07-24 11:05:19 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"79rJgsOSRxNUwP64X7s521KRLG9BEjpC","error":null,"portNumber":60600}'
2017-07-24 11:05:19 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '7,9rJgsOSRxNUwP64X7s521KRLG9BEjpC', error: 'null', listeningPort: '60600''
,ok 217 should be equal
,ok 218 should be equal
,ok 219 should be equal
,2017-07-24 11:05:19 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 07DC7689-843B-41FF-8F84-A0AFB584488F (syncValue: cgyBhKJUgKFE9Zo7yf696BrUb7K5Ofzr)'
2017-07-24 11:05:19 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60606
2017-07-24 11:05:23 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"cgyBhKJUgKFE9Zo7yf696BrUb7K5Ofzr",,"error":null,"portNumber":60606}'
2017-07-24 11:05:23 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'cgyBhKJUgKFE9Zo7yf696BrUb7K5Ofzr', error: 'null', listeningPort: '60606''
,ok 220 should be equal
,ok 221 should be equal
,ok 222 should be equal
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:05:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:D2BCE3C4-528F-472A-A98F-01BEF298D54C
2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdat,eNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:C1DE2F08-A697-4531-80C7-AC50F60F4088
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60600
[ThaliCore] Session.disconnect() peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] TCPListener.socketDidDisc,onnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7
,[ThaliCore] Session.deinit peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:07DC7689-843B-41FF-8F84-A0AFB584488F
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCP,Listener.stopListeningForConnectionsAndDisconnectClients() port:60606
[ThaliCore] Session.disconnect() peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC47B1DF-2B3B-475B-999E-F4C699022015 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "D2BCE3C4-528F-472A-A98F-01BEF298D54C", generation: 0)
,[ThaliCore] Session.deinit peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:05:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:17F49D1B-C74F-4A83-8D4D-3EE1DE7202C7
,# #startListeningForAdvertisements should fail if start not called
,ok 223 specific error should be returned
,# teardown
,ok 224 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-24 11:05:25 - DEBUG thaliMobileNativeWrapper: 'listening 60610'
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
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'listening 60611'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4C9C10B5-CBFE-46FC-A673-3FEFA13CA7AF
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
,[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 232 must be stopped
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
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'listening 60612'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A613E314-4E7C-4E21-9F86-9D6ECD8F6923", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:A613E314-4E7C-4E21-9F86-9D6ECD8F6923
2017-07-24 1,1:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 233 no errors
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A613E314-4E7C-4E21-9F86-9D6ECD8F6923", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:A613E31,4-4E7C-4E21-9F86-9D6ECD8F6923
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 234 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:A613E314-4E7C-4E21-9F86-9D6ECD8F6923
,[ThaliCore] Advertiser.stopAdvertising() peerID:A613E314-4E7C-4E21-9F86-9D6ECD8F6923
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
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'listening 60615'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 236 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:05:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 238 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:27 -, DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {,"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:27 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'listening 60616'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:AAC96A03-8487-4AEA-9B0E-CC4C7BBEA512
[ThaliCore] Browser.st,artListening
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingAc,tive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "DC1479D7-D7AA-4BD7-9E2E-31D7D7990F1C", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:DC1479D7-D7AA-4BD7-9E2E-31D7D7990F1C
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
,ok 243 all connection succeed
,# teardown
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}]'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}]'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:28 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:DC1479D7-D7AA-4BD7-9E2E-31D7D7990F1C
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'listening 60619'
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:83DBC9A8-4F12-4C90-B064-EC5885C39A39
[ThaliCore] Browser.st,artListening
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "921E2A54-60C,3-42A9-9E0C-D873A83A10CE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:921E2A54-60C3-42A9-9E0C-D873A83A10CE
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 245 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1DE2F08-A697-4531-80C7-AC50F60F4088:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1DE2F08-A697-4531-80C7-AC50F60F4088", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}]'
2017-07-24 11:05:28 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","generation":0}'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}]'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:921E2A54-60C3-42A9-9E0C-D873A83A10CE
,2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:05:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 246 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
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
,# all services are stopped when we call stop
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'listening 60621'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:70DAB209-0B6A-446F-8E6A-A6A7165E4019
[ThaliCore] Browser.startListening
2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "8F3A52FC-F00D-4824-AA46-549B6E439409", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:8F3A52FC-F00D-4824-AA46-549B6E439409
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:8F3A52FC-F00D-4824-AA46-549B6E439409
,2017-07-24 11:05:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:30 - INFO thaliMobile: 'Filtered out d,iscoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-24 11:05:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 258 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:31 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:31 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
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
,2017-07-24 11:05:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:33 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:05:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 60624'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:8A2F7F3F-8378-4151-8EFB-FA5D7927C39B
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 268 discoveryActive matches
,ok 269 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 270 discoveryActive matches
,ok 271 advertisingActive matches
,2017-07-24 11:05:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 60625'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "14E8D998-B31C-4C60-BA06-8DB1743779C8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:14E8D998-B31C-4C60-BA06-8DB1743779C8
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 272 discoveryActive matches
,ok 273 advertisingActive matches
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:14E8D998-B31C-4C60-BA06-8DB1743779C8
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,onTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 discoveryActive matches
,ok 275 advertisingActive matches
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,2017-07-24 11:05:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 60627'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'listening 60628'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D41A4DF3-E9BB-4BD5-91AC-0AAA57F2A02B
[ThaliCore] Browser.startListening
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:86C127E7-58B5-42BA-8ABA-1587918D0BF8
2017-07-24 1,1:05:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:05:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-24 11:05:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
2017-07-24 11:05:34 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}]'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}'
,2017-07-24 11:05:34 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"generation":0,"portNumber":null}'
,ok 277 portNumber equal null
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}]'
2017-07-24 11:05:35 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}'
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}]'
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}'
,2017-07-24 11:05:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:86C127E7-58B5-42BA-8ABA-1587918D0BF8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "86C127E7-58B5-42BA-8ABA-1587918D0BF8", generation: 0)
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:86C127E7-58B5-42BA-8ABA-1587918D0BF8
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
2017-07-24 11:05:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 278 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
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
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'listening 60630'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:D15069AD-B38D-4EF4-A83B-D237CEC6E2FD
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:687F0B91-75C2-4D17-A950-AE8032F5F447
,2017-07-24 11:05:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 11:05:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
2017-07-24 11:05:37 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE,986934","peerAvailable":true,"generation":0,"portNumber":null}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"pe,erIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 21C76FB1-27B2-410D-9F47-FB2CAE986934 (syncValue: 1jZOkmUveFAOXFoNHLj4Zz9JeuyTqeBV)'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21,C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BF26BDFD-8E8A-4A40-9359-CD7F3626111F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BF26BDFD-8E8A-4A40-9359-CD7F3626111F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withD,iscoveryInfo:) found peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","generatio,n":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:687F0B91-75C2-4D17-A950-AE8032F5F4,47:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","generation":0}]'
2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE",",generation":0}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:05:37 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"BF26BDFD-8E8A-4A40-9359-CD7F3626111F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:05:37 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:38 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:38 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:38 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:21,C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,1C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
2017-07-24 11:05:43 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}]'
2017-07-24 11:05:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","generation":0}'
,2017-07-24 11:05:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:05:43 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:21,C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,1C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "21C76FB1-27B2-410D-9F47-FB2CAE986934", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:05:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1jZOkmUveFAOXFoNHLj4Zz9JeuyTqeBV","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:05:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '1jZOkmUveFAOXFoNHLj4Zz9JeuyTqeBV', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:05:43 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:05:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:43 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:43 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"21C76FB1-27B2-410D-9F47-FB2CAE986934","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:21C76FB1-27B2-410D-9F47-FB2CAE986934
,2017-07-24 11:05:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 11:05:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 07DC7689-843B-41FF-8F84-A0AFB584488F (syncValue: XFFCJjAJYjldMAv9QIaFdWQ8xONWTTG8)'
,2017-07-24 11:05:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:21C76FB1-27B2-410D-9F47-FB2CAE986934:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
2017-07-24 11:05:44 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}]'
2017-07-24 11:05:44 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","generation":0}'
,2017-07-24 11:05:44 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:05:44 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:07,DC7689-843B-41FF-8F84-A0AFB584488F:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,7DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "07DC7689-843B-41FF-8F84-A0AFB584488F", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:05:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XFFCJjAJYjldMAv9QIaFdWQ8xONWTTG8","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:05:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XFFCJjAJYjldMAv9QIaFdWQ8xONWTTG8', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:05:46 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:05:46 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:05:46 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:05:46 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:05:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"07DC7689-843B-41FF-8F84-A0AFB584488F","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:07DC7689-843B-41FF-8F84-A0AFB584488F
2017-07-24 11:05:46 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-24 11:05:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0E534893-77FF-4F66-BCDB-4AC9A7F7D71A (syncValue: Z7ztXXwD7A5Wsoti4jKCHBFUeRNIrxI7)'
2017-07-24 11:05:46 - DEBUG thaliMobileNativeTestUt,i,ls: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:07DC7689-843B-41FF-8F84-A0AFB584488F:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFD4D396-F97C-4CF0-BB77-E18834A0319F
[ThaliCore] Advertiser: session connected Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CFD4D396-F97C-4CF0-BB77-E18834A0319F state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60638
2017-07-24 11:05:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"Z7ztXXwD7A5Wsoti4jKCHBFUeRNIrxI7",,"error":null,"portNumber":60638}'
,2017-07-24 11:05:50 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'Z7ztXXwD7A5Wsoti4jKCHBFUeRNIrxI7', error: 'null', listeningPort: '60638''
,2017-07-24 11:05:50 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [2, 17]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:05:50 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:05:50 - DEBUG testUtils: 'Got end'
,ok 279 response body should match testData
,ok 280 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CFD4D396-F97C-4CF0-BB77-E18834A0319F
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFD4D396-F97C-4CF0-BB77-E18834A0319F state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFD4D396-F97C-4CF0-BB77-E18834A0319F
[ThaliCore] Session.startOutputStream(with:) peer:CFD4D396-F97C-4CF0-BB77-E18834A0319F
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,8 [2, 17, 18]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22
[ThaliCore] Advertiser: session connected Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22
,[ThaliCore] Session.session(_:peer:didChange:) peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22
[ThaliCore] Session.startOutputStream(with:) peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1,9 [2, 17, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:687F0B91-75C2-4D17-A950-AE8032F5F447
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:05:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:05:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 281 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:05:56 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.disconnect peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A
[ThaliCore] BrowserRelay.closeRel,ay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60638
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(,Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optio,nal(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket exited RunLoop vsID:17
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:19
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:18
,[ThaliCore] Session.disconnect() peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
,[ThaliCore] VirtualSocket.deinit vsID:17 [2, 18, 19]
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] VirtualSock,et.closeStreams() vsID:18
,[ThaliCore] TCPListener.deinit
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeStreams() vsID:19
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[T,haliCore] VirtualSocket exited RunLoop vsID:19
[ThaliCore] VirtualSocket.deinit vsID:19 [2, 18]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:18
,[ThaliCore] VirtualSocket.deinit vsID:18 [2]
,[ThaliCore] Session.session(_:peer:didChange:) peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22
[ThaliCore] Advert,iserRelay.deinit
,[ThaliCore] Session.deinit peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:05:56 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFD4D396-F97C-4CF0-BB77-E18834A0319F state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "687F0B91-75C2-4D17-A950-AE8032F5F447", generation: 0)
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:05:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:17F0E4CA-AFA5-42FB-BD68-6F50E15C1E22
,# can still do HTTP requests between peers with coordinator
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'listening 60642'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6C097E42-E518-480B-9D1F-E821DF619B8A
,[ThaliCore] Browser.startListening
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:05:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:05:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:951E5565-7CD1-4438-B15D-EB97D09CF081
,2017-07-24 11:05:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:05:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-24 11:05:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","generation":0}]'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","generation":0}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}]'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for A24BFF38-9898-41C6-87EB-9ADA562612FE (syncValue: jb91ym3JKGjfz5WRffWvSYZzRqMrSmjd)'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
2017-07-24 11:05:58 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}]'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:951E5565-7CD1-4438-B15D-EB97D09CF081:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "951E5565-7CD1-4438-B15D-EB97D09CF081", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:076336D2-906B-45A8-9499-6D7BDC53DCA7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "076336D2-906B-45A8-9499-6D7BDC53DCA7", generation: 0)
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","generation":0}]'
2017-07-24 11:05:58 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","generation":0}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:05:58 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:05:58 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,4BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,4BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,4BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "A,24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:A2,4BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "A24BFF38-9898-41C6-87EB-9ADA562612FE", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:A24BFF38,-9898-41C6-87EB-9ADA562612FE error: max retries exceeded
2017-07-24 11:06:09 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"jb91ym3JKGjfz5WRffWvSYZzRqMrSmjd","error":"Connection could not be established","portNumber":null}'
2017-0,7-24 11:06:09 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'jb91ym3JKGjfz5WRffWvSYZzRqMrSmjd', error: 'Connection could not be established', listeningPort: '%s''
2017-07-24 11:06:09 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {,"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:09 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:06:09 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-24 11:06:09 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-24 11:06:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-24 11:06:09 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,i,er":"A24BFF38-9898-41C6-87EB-9ADA562612FE","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:09 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-24 11:06:09 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 0E534893-77FF-4F66-BCDB-4AC9A7F7D71A (syncValue: 6NRpTvtA23rlOkZB6DEOHsPthkhjWOqx)'
,2017-07-24 11:06:09 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:A24BFF38-9898-41C6-87EB-9ADA562612FE:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0E,534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
2017-07-24 11:06:12 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}]'
2017-07-24 11:06:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","generation":0}'
,2017-07-24 11:06:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:06:12 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:0E,534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "0,E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "0E534893-77FF-4F66-BCDB-4AC9A7F7D71A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:06:14 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6NRpTvtA23rlOkZB6DEOHsPthkhjWOqx","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:06:14 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '6NRpTvtA23rlOkZB6DEOHsPthkhjWOqx', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:06:14 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:14 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:14 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:06:14 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-24 11:06:14 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peer,Identifier":"0E534893-77FF-4F66-BCDB-4AC9A7F7D71A","peerAvailable":true,"portNumber":null,"recreated":true}'
[ThaliCore] BrowserManager.disconnect peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A
2017-07-24 11:06:14 - ERROR thaliMobileNativeTestUtils: 'Fatal co,nnect error: 'Peer is unavailable''
2017-07-24 11:06:14 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BC19DA9F-A334-4CA1-8FCD-469184F8E157 (syncValue: tF9cLQBk1qIMF4FJagyn0oqGR4sxjJ2e)'
,2017-07-24 11:06:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:0E534893-77FF-4F66-BCDB-4AC9A7F7D71A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60660
2017-07-24 11:06:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tF9cLQBk1qIMF4FJagyn0oqGR4sxjJ2e","error":null,"portNumber":60660}'
,2017-07-24 11:06:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tF9cLQBk1qIMF4FJagyn0oqGR4sxjJ2e', error: 'null', listeningPort: '60660''
,2017-07-24 11:06:17 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [2, 20]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:06:17 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:06:17 - DEBUG testUtils: 'Got end'
,ok 282 response body should match testData
,ok 283 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:951E5565-7CD1-4438-B15D-EB97D09CF081
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-24 11:06:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 284 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdate,NonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:18 - DEBUG thali,MobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.di,sconnect peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60660
[ThaliCore] VirtualSocket.closeStreams() vsID:20
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] Bro,wserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:20
[ThaliCore] Session.disconnect() peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCo,re] VirtualSocket.closeStreams() vsID:20
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:20 [2]
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.deinit peer:BC19DA9F-A334-4CA1-8FC,D-469184F8E157:0
[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calls correct starts when network changes
,2017-07-24 11:06:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'calls correct starts when network changes''
,# teardown
,ok 285 must be stopped
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:19 - I,NFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,,"advertisingActive":false}'
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
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests after connections are cut
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'listening 60662'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:42530266-613F-421D-BBC9-A49C425FB20F
,[ThaliCore] Browser.startListening
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9D2D069F-2F60-447B-B8BA-60B087ACB18C", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:9D2D069F-2F60-447B-B8BA-60B087ACB18C
,2017-07-24 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-24 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2E623E57-D644-437A-B062-C493DD079F60:0
2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdent,ifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}]'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}]'
2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BC19DA9F-A334-4CA1-8FCD-469184F8E157 (syncValue: iHpz4DKc2eQ9JEIcqQ5OlrY8llNidgKT)'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}]'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:20 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:20 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9D2D069F-2F60-447B-B8BA-60B087ACB18C:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9D2D069F-2F60-447B-B8BA-60B087ACB18C", generation: 0)
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
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
2017-07-24 11:06:25 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}]'
2017-07-24 11:06:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","generation":0}'
,2017-07-24 11:06:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-24 11:06:25 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
,[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "BC19DA9F-A334-4CA1-8FCD-469184F8E157", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:06:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iHpz4DKc2eQ9JEIcqQ5OlrY8llNidgKT","error":"Peer is unavailable",,"portNumber":null}'
2017-07-24 11:06:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'iHpz4DKc2eQ9JEIcqQ5OlrY8llNidgKT', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-24 11:06:26 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"BC19DA9F-A334-4CA1-8FCD-469184F8E157","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157
,2017-07-24 11:06:26 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-24 11:06:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 2E623E57-D644-437A-B062-C493DD079F60 (syncValue: ot5WGnZG5FTKCXyRlDqOesbK03Eq4jNO)'
,2017-07-24 11:06:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:BC19DA9F-A334-4CA1-8FCD-469184F8E157:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E623E57-D644-437A-B062-C493DD079F60:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E623E57-D644-437A-B062-C493DD079F60:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60672
,2017-07-24 11:06:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ot5WGnZG5FTKCXyRlDqOesbK03Eq4jNO","error":null,"portNumber":60672}'
,2017-07-24 11:06:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ot5WGnZG5FTKCXyRlDqOesbK03Eq4jNO', error: 'null', listeningPort: '60672''
,2017-07-24 11:06:29 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:21 [2, 21]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:06:29 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:06:29 - DEBUG testUtils: 'Got end'
,ok 287 response body should match testData
,ok 288 must be started
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9D2D069F-2F60-447B-B8BA-60B087ACB18C
,2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-24 11:06:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-24 11:06:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 289 must be stopped
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:39 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-24 11:06:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.disconnect peer:2E623E57-D644-437A-B062-C493DD079F60
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60672
[ThaliCore] VirtualSocket.closeStr,eams() vsID:21
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket remo,ved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket exited RunLoop vsID:21
,[ThaliCore] Session.disconnect() peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] VirtualSocket.closeStreams() vsID:21
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
[ThaliCore] VirtualSocket.deinit vsID:21 [2]
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserRelay.deinit
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-24 11:06:39 - DEBUG thaliMobileNat,iveWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-24 11:06:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:06:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-24 11:06:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-07-24 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"C1DE2F08-A697-4531-80C7-AC50F60F4088","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"A24BFF38-9898-41C6-87EB-9ADA562612FE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"076336D2-906B-45A8-9499-6D7BDC53DCA7","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:41 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'listening 60674'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 303 error should be null
,ok 304 error should be null
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,ok 305 error should be null
ok 306 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 307 error should be null
,ok 308 error should be null
,# setup
,ok 309 ThaliMobile should be stopped
,# should be able to call #startListeningForAdvertisements many times
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'listening 60675'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:06905C2F-6AC3-407D-B2EF-F13221B51F17
,[ThaliCore] Browser.startListening
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 310 error should be null
ok 311 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,ok 312 error should be null
ok 313 error should be null
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
# teardown
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}]'
[ThaliCore] Browser.browser(_:foundPeer:withDi,scoveryInfo:) found peer:2E623E57-D644-437A-B062-C493DD079F60:0
2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation",:0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-24 11:06:42 - DEBUG thaliMobile: 'Emit,ting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}]'
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}'
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:42 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:06:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 314 error should be null
,ok 315 error should be null
,# setup
,ok 316 ThaliMobile should be stopped
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'listening 60676'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "28BA2DE0-D658-483E-AF20-61BFD11DD969", generation: 0)
[ThaliCore] Advertiser.startA,dvertising with peerID:28BA2DE0-D658-483E-AF20-61BFD11DD969
2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 317 error should be null
ok 318 error should, be null
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "28BA2DE0-D658-483E-AF20-61BFD11DD969", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:28BA2DE0-D658-483E-AF20-61BFD11DD969
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 319 error should be null
ok 320 error should be null
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:28BA2DE0-D658-483E-AF20-61BFD11DD969
,[ThaliCore] Advertiser.stopAdvertising() peerID:28BA2DE0-D658-483E-AF20-61BFD11DD969
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 321 error should be null
,ok 322 error should be null
,# setup
,ok 323 ThaliMobile should be stopped
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-24 11:06:43 - DEBUG thaliMobileNativeWrapper: 'listening 60679'
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
,2017-07-24 11:06:44 - DEBUG thaliMobileNativeWrapper: 'listening 60680'
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
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"454328db-3636-41ad-9e75-a29d121a499e","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 348 should be called once
ok 349 should not have been called more than once
,# teardown
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"454328db-3636-41ad-9e75-a29d121a499e","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e29abb78-e30f-4ff9-bd31-96178e6462ad","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 358 peer should be available
,ok 359 cache contains native peer
,2017-07-24 11:06:45 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"e29abb78-e30f-4ff9-bd31-96178e6462ad","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 360 peer should be unavailable
,ok 361 peer has been removed from cache
,# teardown
,ok 362 error should be null
,ok 363 error should be null
,# setup
,ok 364 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
,ok 365 we have not added peer to the cache yet
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35a7d178-29a0-45c9-a7cc-844b1de9c805","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 366 peer should be available
,ok 367 cache contains wifi peer
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"35a7d178-29a0-45c9-a7cc-844b1de9c805","connectionType":"tcp","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 368 peer should be unavailable
,ok 369 peer has been removed from cache
,# teardown
,ok 370 error should be null
,ok 371 error should be null
,# setup
,ok 372 ThaliMobile should be stopped
,# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"88232fd2-c9ed-481d-b6be-f838134f29d6","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 373 first peer is available
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"252a9522-7ace-4028-bfd4-b15794502bff","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 374 second peer is available
,ok 375 first and second peers are different
,# teardown
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"88232fd2-c9ed-481d-b6be-f838134f29d6","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"252a9522-7ace-4028-bfd4-b15794502bff","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 376 error should be null
,ok 377 error should be null
,# setup
,ok 378 ThaliMobile should be stopped
,# native available - new peer is cached
,ok 379 should not be in cache at start
2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b550efcc-e5e1-467a-a0be-d0680a6e0ada","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddr,essPort":false}'
ok 380 peer is available
,# teardown
,2017-07-24 11:06:46 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b550efcc-e5e1-467a-a0be-d0680a6e0ada","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3edf7a77-450b-42b6-b2fc-cb8fe53555eb","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 390 peer should be available
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"3edf7a77-450b-42b6-b2fc-cb8fe53555eb","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 391 peer should be available
,ok 392 should store correct generation
,# teardown
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"3edf7a77-450b-42b6-b2fc-cb8fe53555eb","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 393 error should be null
,ok 394 error should be null
,# setup
,ok 395 ThaliMobile should be stopped
,# native available - peer with same or older generation is ignored (MPCF)
,2017-07-24 11:06:47 - DEBUG thaliMobileNativeWrapper: 'listening 60681'
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c996dd4d-26cd-4a63-8a83-4d7b2dd299f0","connectionType":"MPCF","peerAvailable":true,"generation":2,"newAddressPort":false}'
,ok 396 discovered correct peer
,ok 397 got correct generation
,2017-07-24 11:06:47 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"c996dd4d-26cd-4a63-8a83-4d7b2dd299f0","connectionType":"MPCF","peerAvailable":true,"generation":3,"newAddressPort":false}'
,ok 398 discovered correct peer
,ok 399 got correct generation
,# teardown
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c996dd4d-26cd-4a63-8a83-4d7b2dd299f0","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 11:06:48 - DEBUG thaliMobileNativeWrapper: 'listening 60682'
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4971828f-0dc5-4805-b118-8d901c071832","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 403 discovered available peer
,ok 404 peer is available
,# teardown
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4971828f-0dc5-4805-b118-8d901c071832","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b1ae0eb0-5efd-44de-8baa-fd255a752340","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 408 peer should be available
,2017-07-24 11:06:48 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b1ae0eb0-5efd-44de-8baa-fd255a752340","connectionType":"MPCF","peerAvailable":false,"generation":0,"newAddressPort":null}'
,ok 409 peer should be unavailable
,ok 410 should be removed from cache
,# teardown
,ok 411 error should be null
,ok 412 error should be null
,# setup
,ok 413 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for wifi peers
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'listening 60683'
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2e872de4-9ed0-4ded-9119-40f401bdcfad","connectionType":"MPCF","peerAvaila,ble":true,"generation":0,"newAddressPort":false}'
ok 414 first peer is expected to be available
2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f209fb46-4c6b-4687-a09f-7a9145bf5182","connectio,nType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 415 second peer is expected to be available
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f209fb46-4c6b-4687-a09f-7a9145bf5182","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 416 peer became unavailable
,ok 417 it was wifi peer
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"f209fb46-4c6b-4687-a09f-7a9145bf5182","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 418 we found peer again
,ok 419 it was wifi peer
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"f209fb46-4c6b-4687-a09f-7a9145bf5182","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 420 peer became unavailable
,ok 421 it was wifi peer
,# teardown
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"2e872de4-9ed0-4ded-9119-40f401bdcfad","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 426 error should be null
,# setup
,ok 427 ThaliMobile should be stopped
,# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
,2017-07-24 11:06:49 - DEBUG thaliMobileNativeWrapper: 'listening 60684'
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"b69aae88-fca1-4008-a04e-b7f04a37d25c","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 428 first peer is expected to be available
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"848df8c2-1c4f-4a79-bcf7-57cd56011899","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 429 second peer is expected to be available
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"b69aae88-fca1-4008-a04e-b7f04a37d25c","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,ok 430 peer became unavailable
,2017-07-24 11:06:49 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"848df8c2-1c4f-4a79-bcf7-57cd56011899","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 11:06:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
,# teardown
,ok 438 error should be null
,ok 439 error should be null
,# setup
,ok 440 ThaliMobile should be stopped
,# newAddressPort field (TCP_NATIVE)
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ddff42a3-0af7-4f46-8edc-f5f3545f2a38","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 441 peer discovered first time does not have new address
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ddff42a3-0af7-4f46-8edc-f5f3545f2a38","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":false}'
,ok 442 address has not been changed
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ddff42a3-0af7-4f46-8edc-f5f3545f2a38","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 443 new port handled correctly
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ddff42a3-0af7-4f46-8edc-f5f3545f2a38","connectionType":"tcp","peerAvailable":true,"generation":20,"newAddressPort":true}'
,ok 444 new host handled correctly
,2017-07-24 11:06:50 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ddff42a3-0af7-4f46-8edc-f5f3545f2a38","connectionType":"tcp","peerAvailable":false,"generation":20,"newAddressPort":null}'
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
,ok 457 error should be null
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
,2017-07-24 11:06:51 - DEBUG CoordinatedClient: 'test was skipped, name: '#getPeerHostInfo - returns discovered cached native peer (BLUETOOTH)''
,# teardown
,ok 463 error should be null
ok 464 error should be null
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
,ok 470 error should be null
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
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'listening 60685'
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ac2bb5be-6ca4-464a-9842-5b80eaa598e4","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 478 Got specific error message
,# teardown
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ac2bb5be-6ca4-464a-9842-5b80eaa598e4","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,2017-07-24 11:06:52 - DEBUG thaliMobileNativeWrapper: 'listening 60686'
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"01053e45-28b0-4792-8a5d-f426a252b2e4","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] BrowserManager.disconnect peer:01053e45-28b0-4792-8a5d-f426a252b2e4
,ok 482 native wrapper `disconnect` called once
,ok 483 native wrapper `disconnect` called with peer data
,# teardown
,2017-07-24 11:06:52 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"01053e45-28b0-4792-8a5d-f426a252b2e4","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
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
,ok 497 error should be null
,# setup
,ok 498 ThaliMobile should be stopped
,# We properly fire peer unavailable and then available when connection fails on iOS
,2017-07-24 11:06:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails on iOS''
,# teardown
,ok 499 error should be null
,ok 500 error should be null
,# setup
,ok 501 ThaliMobile should be stopped
,# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
,2017-07-24 11:06:54 - DEBUG CoordinatedClient: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
,# teardown
,ok 502 error should be null
,ok 503 error should be null
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
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'listening 60687'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BE0B32E4-B276-47B0-B248-F1E7376FA19A
,[ThaliCore] Browser.startListening
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"faf2ff8d-af7b-4946-bafc-94835613e357","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 508 Peer availabilities has one entry for our connection type
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"7ad1b5e3-3d33-450b-a320-ad98bb8c047a","connectionType":"tcp","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 509 Peer availabilities has one entry for our connection type
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"faf2ff8d-af7b-4946-bafc-94835613e357","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:54 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7ad1b5e3-3d33-450b-a320-ad98bb8c047a","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"pskIdToSecret":[102,111,1,11],"networkType":"BOTH"}})'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-24 11:06:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:06:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-24 11:06:55 - DEBUG thaliMobileNativeWrapper: 'listening 60688'
,2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"d7a8c349-579c-426f-99a7-dd9b404afe61","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,ok 516 1
,ok 517 2
,2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"ed88cb4c-a545-4ee8-8e93-5382a6a15cdd","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,# teardown
,2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d7a8c349-579c-426f-99a7-dd9b404afe61","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:06:55 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ed88cb4c-a545-4ee8-8e93-5382a6a15cdd","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore,] AdvertiserManager.stopAdvertising()
2017-07-24 11:06:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-24 11:06:55 - INFO thaliMobile: 'Filtered out discoveryAdvert,isingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-24 11:06:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017,-07-24 11:06:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:06:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'listening 60689'
,ok 524 error should be null
,ok 525 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,ok 526 error should be null
,ok 527 error should be null
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C1D1D0FB-7A54-4F71-806C-1013F6702C89
,[ThaliCore] Browser.startListening
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,ok 528 error should be null
,ok 529 error should be null
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}]'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}]'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2E623E57-D644-437A-B062-C493DD079F60 (syncValue: 0)'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2E623E57-D644-437A-B062-C493DD079F60:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}]'
2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","generation":0}'
,2017-07-24 11:06:56 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:06:56 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","generation":0}]'
2017-07-24 11:06:57 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","generation":0}'
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","generation":0}]'
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","generation":0}'
,2017-07-24 11:06:57 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:06:57 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:2E623E57-D644-437A-B062-C493DD079F60:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:2E,623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2,E623E57-D644-437A-B062-C493DD079F60", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2E623E57-D644-437A-B062-C493DD079F60", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"0","error":"Peer is unavailable","portNumber":null}'
2017-07-2,4 11:06:59 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:06:59 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 10087D13-05EC-4EC5-A858-75B42091AB0B (syncValue: 1)'
2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,2017-07-24 11:06:59 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:06:59 - DEBUG thali,MobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2E623E57-D644-437A-B062-C493DD079F60","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:2E623E57-D644-437A-B062-C493DD079F60:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,2017-07-24 11:07:01 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}]'
,2017-07-24 11:07:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","generation":0}'
,2017-07-24 11:07:01 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:07:01 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:10,087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,0087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "10087D13-05EC-4EC5-A858-75B42091AB0B", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-24 11:07:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1","error":"Peer is unavailable","portNumber":null}'
2017-07-2,4 11:07:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:07:02 - DEBUG thaliMobileNativeWr,apper: 'Received peer availability changed event with {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:02 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CAD31C85-20E6-4BD1-A48E-7A308E222915 (syncValue: 2)'
2017-07-24 11:07:02 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnec,ted:stoppedListening:)
,2017-07-24 11:07:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-24 11:07:02 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"10087D13-05EC-4EC5-A858-75B42091AB0B","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] Session.deinit peer:10087D13-05EC-4EC5-A858-75B42091AB0B:0
[ThaliCore] BrowserRelay.deinit
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Advertiser: session connect,ed Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698,DB state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
[ThaliCore] Session.session(_:peer:didChange:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
,[ThaliCore] Session.session(_:peer:didChange:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Session.startOutputStream(with:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [2, 22]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60698
2017-07-24 11:07:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"2","error":null,"portNumber":60698,}'
,2017-07-24 11:07:05 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 9EED0799-F500-45EE-9882-03BB7687C630 (syncValue: 3)'
2017-07-24 11:07:05 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectToPee,r(_:syncValue:retryCount:completion:) Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", ge,neration: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:23 [2, 22, 23]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:05 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:07:05 - DEBUG testUtils: 'Got end'
,[ThaliCore] Session.session(_:peer:didChange:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
,[ThaliCore] Session.session(_:peer:didChange:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
,[ThaliCore] Session.startOutputStream(with:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:24 [2, 22, 23, 24]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60703
2017-07-24 11:07:08 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":null,"portNumber":60703,}'
,[ThaliCore] BrowserManager.disconnect peer:2E623E57-D644-437A-B062-C493DD079F60
,[ThaliCore] BrowserManager.disconnect peer:10087D13-05EC-4EC5-A858-75B42091AB0B
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:25 [2, 22, 23, 24, 25]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:08 - DEBUG testUtils: 'Got response data'
,2017-07-24 11:07:08 - DEBUG testUtils: 'Got end'
,ok 530 received all uuids
,# teardown
,2017-07-24 11:07:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:07:09 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8
,2017-07-24 11:07:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:07:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 11:07:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:25
[ThaliCore] VirtualSocket.closeStreams() vsID:25
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:25
[ThaliCore] VirtualSocket.deinit vsID:25 [2, 22, 23, 24]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socke,t removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 11:07:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:07:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:07:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalize,dDescription=Socket closed by remote peer})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:24
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] Virt,ualSocket.closeStreams() vsID:24
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:22
[ThaliCore] VirtualSocket.closeStreams() vsID:22
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:24
[ThaliCore] VirtualSocket.deinit vsID:24 [2, 22, 23]
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler dis,connecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:22
,[ThaliCore] VirtualSocket.deinit vsID:22 [2, 23]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:23
,[ThaliCore] VirtualSocket.closeStreams() vsID:23
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:23
[ThaliCore] VirtualSocket.deinit vsID:23 [2]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 531 error should be null
,ok 532 error should be null
,# setup
,ok 533 ThaliMobile should be stopped
,# test for data corruption
,2017-07-24 11:07:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'test for data corruption''
,# teardown
,ok 534 error should be null
ok 535 error should be null
# setup
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
,2017-07-24 11:07:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 544 after kill
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
,ok 596 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 597 Queue is empty
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
,ok 614 queue is not empty
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
,ok 619 already enqueued
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
,ok 628 first kill
,ok 629 second NOOP kill
,# teardown
,# setup
,# #ThaliPeerPoolInterface - make sure that stop removes all actions
,ok 630 1st good enqueue
,ok 631 2nd good enqueue
,ok 632 1st action is in the pool
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
,ok 643 Got null
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
ok 658 Null 1
ok 659 (unnamed assert)
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidBlu,etooth, Peer Identifier: notificationAction'
ok 660 is an agent
,ok 661 Null 3
ok 662 Replication not yet called
ok 663 Notification 2 not yet called
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 590, Action Type: GetRequestBeacon, Connection Type: AndroidB,luetooth, Peer Identifier: notificationAction'
2017-07-24 11:07:21 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 591, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
ok 664 is an agent,
ok 665 Notification went first
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
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'listening 60707'
,ok 679 error should be null
,ok 680 error should be null
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B
,2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:4306BA2F-32FE-44A1-8501-AFDD58B1532E
[ThaliCore] Browser.startListening
2017-07-24 11:07:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-24 11:07:22 - INFO testThaliNotification: 'startListeningForAdvertisements'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
,[ThaliCore] Session.startOutputStream(with:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:26 [2, 26]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:26
[ThaliCore] VirtualSocket.closeStreams() vsID:26
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:26
,[ThaliCore] VirtualSocket.deinit vsID:26 [2]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Session.startOutputStream(with:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,7 [2, 27]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=61 "Connection refused" UserInfo={NSLocalizedDescription=Connection refused, NSLocalizedFailureReason=Error in connect() ,function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:27
[ThaliCore] VirtualSocket.closeStreams() vsID:27
[ThaliCore] AdvertiserRelay.did,CloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] Session.startOutputStream(with:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,8 [2, 27, 28]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=0 "Undefined error: 0" UserInfo={NSLocalizedDescription=Undefined error: 0, NSLocalizedFailureReason=Error in connect() f,unction})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:28
[ThaliCore] VirtualSocket.closeStreams() vsID:28
[ThaliCore] AdvertiserRelay.didC,loseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:28
[ThaliCore] VirtualSocket.deinit vsID:28 [2, 27]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
[ThaliCore] Session.startOutputStream(with:) peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,9 [2, 27, 29]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=NSPOSIXErrorDomain Code=1 "Operation not permitted" UserInfo={NSLocalizedDescription=Operation not permitted, NSLocalizedFailureReason=Error in c,onnect() function})
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:29
[ThaliCore] VirtualSocket.closeStreams() vsID:29
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:29
,[ThaliCore] VirtualSocket.deinit vsID:29 [2, 27]
,[ThaliCore] Session.session(_:peer:didChange:) peer:9EED0799-F500-45EE-9882-03BB7687C630:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:60703
[ThaliCore] Session.disconnect() peer:9EED0799-F500-45EE-9882-03BB7687C630:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Browser: session notConnected fire not,ification for Peer(uuid: "9EED0799-F500-45EE-9882-03BB7687C630", generation: 0)
2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3","error":"Session disconnected","portNumber":null}'
2017-07-24 11:07:26 - DEBUG t,haliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Received pe,er availability changed event with {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"9EED0799-F500-45EE-9882-03BB7687C630","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:9EED0799-F500-45EE-9882-03BB7687C630
,[ThaliCore] Session.deinit peer:9EED0799-F500-45EE-9882-03BB7687C630:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notC,onnected:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
[ThaliCore] Advertiser: session connected Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconn,ect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92 state: notConnected -> connecting
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:764C631C-B170-4A40-9D06-97350890569E
[ThaliCore] ,Advertiser: session connected Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
[ThaliCore] Session.session(_:peer:didChange:) peer:764C631C-B170-4A40-9D06-97350890569E state: notConnected -> connecting
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915",,"generation":0}]'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","generation":0}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD34390017FE","generation":0}]'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD34390017FE","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:07:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD34390017FE","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:07:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD34390017FE","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CAD31C85-20E6-4BD1-A48E-7A308E222915 (syncValue: 4)'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC9AF43F-E75B-4A72-9E65-674DD3ABC08B", generation: 0)
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0) found active relay
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"4","error":null,"portNumber":60698}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 4F51A3C8-A689-4B82-BAD8-DD34390017FE (syncValue: 5)'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","generation":0}]'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","generation":0}'
,2017-07-24 11:07:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:07:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:30 [2, 27, 30]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:30
[ThaliCore] VirtualSocket.closeStreams() vsID:30
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:30
,[ThaliCore] VirtualSocket.deinit vsID:30 [2, 27]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,2017-07-24 11:07:26 - DEBUG thaliPeerPoolDefault: 'Got err   Could not establish TCP connection'
,[ThaliCore] Session.session(_:peer:didChange:) peer:645FEF10-D49D-4B2D-B053-3BA6A5F698DB state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "F19FF286-5FF4-414C-B92A-B7A0BDE3CBB8", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
,[ThaliCore] Session.deinit peer:D16BD50F-C9C6-4E04-8017-9734AD507B83
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:764C631C-B170-4A40-9D06-97350890569E
,[ThaliCore] Session.session(_:peer:didChange:) peer:764C631C-B170-4A40-9D06-97350890569E state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4F51A3C8-A689-4B82-BAD8-DD34390017FE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60715
2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5","error":null,"portNumber":60715,}'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 12B63DC0-3AAD-4086-9C02-4C78DF1E4303 (syncValue: 6)'
,2017-07-24 11:07:29 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:31 [2, 27, 31]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
,[ThaliCore] Session.startOutputStream(with:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:32 [2, 27, 31, 32]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:764C631C-B170-4A40-9D06-97350890569E
[ThaliCore] Session.startOutputStream(with:) peer:764C631C-B170-4A40-9D06-97350890569E
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,3 [2, 27, 31, 32, 33]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
[ThaliCore] Session.startOutputStream(with:) peer:C3A5A23A-A572-40C3-83C5-7F24353B1E92
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3,4 [2, 27, 31, 32, 33, 34]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:32
[ThaliCore] VirtualSocket.closeStreams() vsID:32
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:32
,[ThaliCore] VirtualSocket.deinit vsID:32 [2, 27, 31, 33, 34]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0 state: notConnected -> connecting
,2017-07-24 11:07:30 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 60715,4F51A3C8-A689-4B82-BAD8-DD34390017FE'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:31
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:31
[ThaliCore] VirtualSocket.deinit vsID:31 [2, 27, 33, 34]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4F51A3C8-A689-4B82-BAD8-DD34390017FE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:35 [2, 27, 33, 34, 35]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:34
[ThaliCore] VirtualSocket.closeS,treams() vsID:34
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:34
,[ThaliCore] VirtualSocket.deinit vsID:34 [2, 27, 33, 35]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:764C631C-B170-4A40-9D06-97350890569E
,[ThaliCore] Session.startOutputStream(with:) peer:764C631C-B170-4A40-9D06-97350890569E
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:36 [2, 27, 33, 35, 36]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:33
[ThaliCore] VirtualSocket.closeStreams() vsID:33
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:36
[ThaliCore] VirtualSocket.closeS,treams() vsID:36
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:36
,[ThaliCore] VirtualSocket.deinit vsID:36 [2, 27, 33, 35]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:35
[ThaliCore] VirtualSocket.closeStreams() vsID:35
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:35
[ThaliCore] VirtualSocket.deinit vsID:35 [2, 27, 33]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket re,moved, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:60698
[ThaliCore] Session.disconnect() peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:CAD31C85-20E6-4BD1-A48E-7A308E222915:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0) relay removed
[ThaliCore] BrowserRelay.deinit
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","generation":0}]'
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","generation":0}'
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-24 11:07:32 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:07:32 - WARN thaliNotificationClient: 'peer is not available'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "12B63DC0-3AAD-4086-9C02-4C78DF1E4303", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60724
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"6","error":null,"portNumber":60724}'
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for CAD31C85-20E6-4BD1-A48E-7A308E222915 (syncValue: 7)'
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CAD31C85-20E6-4BD1-A48E-7A308E222915", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7","error":"Peer is unavailable","portNumber":null}'
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-24 11:07:32 - DEBUG thaliPeerPoolDefault: 'Got err   Peer is unavailable'
,2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
2017-07-24 11:07:32 - DEBUG thaliMobileNativeWrapper: 'han,dlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CAD31C85-20E6-4BD1-A48E-7A308E222915","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:CAD31C85-20E6-4BD1-A48E-7A308E222915
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:37 [2, 27, 33, 37]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:07:33 - INFO testThaliNotification: 'PeerAdvertisesDataForUs:MPCF, 127.0.0.1, 127.0.0.1, 60724,12B63DC0-3AAD-4086-9C02-4C78DF1E4303'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:37
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:12B63DC0-3AAD-4086-9C02-4C78DF1E4303:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:38 [2, 27, 33, 37, 38]
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler st,ate:connected
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] VirtualSocket exited RunLoop vsID:37
[ThaliCore] VirtualSocket.deinit vsID:37 [2, 27, 33, 38]
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:38
[ThaliCore] VirtualSocket.closeStreams() vsID:38
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:38
[ThaliCore] VirtualSocket.deinit vsID:38 [2, 27, 33]
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:nil
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,ok 681 Peer made successful https requests to all peers
,ok 682 Peer received right amount of https requests
,ok 683 HTTPS server received zero PSK Identities. Count:0
,# teardown
,2017-07-24 11:07:37 - INFO testThaliNotification: 'Participants:3 Peers Replied to us:2 Peers requested to:2'
,2017-07-24 11:07:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"4F51A3C8-A689-4B82-BAD8-DD34390017FE","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-24 11:07:37 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"12B63DC0-3AAD-4086-9C02-4C78DF1E4303","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:EC9AF43F-E75B-4A72-9E65-674DD3ABC08B
,2017-07-24 11:07:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-24 11:07:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{}})'
,2017-07-24 11:07:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-24 11:07:37 - DEBUG thaliMobileNativeW,rapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:07:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-24 11:07:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-24 11:07:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-24 11:07:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,# Test BEACONS_RETRIEVED_AND_PARSED locally
,ok 684 peerIdentifier should match
ok 685 generation should match
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
ok 693 must return null after successful call
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
ok 702 Start after killed
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
ok 733 should be equal
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
ok 748 keys match
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
2017-07-24 11:07:58 - WARN thaliNotificationClient: 'peer is not available'
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
,ok 763 Peer state should be RESOLVED
,# teardown
,2017-07-24 11:08:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Resolves an action locally
,ok 764 hostAddress must match
ok 765 portNumber must match
ok 766 suggestedTCPTimeout must match
ok 767 connectionType must match
ok 768 peerIDs must match
# teardown
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
ok 776 action should be resolved with NETWORK_PROBLEM error
,2017-07-24 11:08:03 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 777 action should be resolved with NETWORK_PROBLEM error
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
,2017-07-24 11:08:06 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 782 peerDictionary should become empty
,# teardown
,2017-07-24 11:08:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# notificationClient does not retry action with BAD_PEER resolution
,2017-07-24 11:08:06 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
,ok 783 failed with expected error
ok 784 peer state should be RESOLVED
,# teardown
,2017-07-24 11:08:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
,ok 788 Public key matches with the server key
,ok 789 hostAddress must match
,ok 790 portNumber must match
,ok 791 suggestedTCPTimeout must match
,ok 792 connectionType must match
,# teardown
,2017-07-24 11:08:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Test ThaliPskMapCache clean and expiration
,ok 793 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 794 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
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
,ok 799 Cache doesn't contain dictionary1
,ok 800 Size of the cache should be 1
,ok 801 Cache doesn't contain beaconStreamAndSecretDictionary2
,# teardown
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
,ok 816 should be 204
,# teardown
,2017-07-24 11:08:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# Make an HTTP request to /NotificationBeacons (no keys)
,ok 817 error should be null
,ok 818 should be 204
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
,ok 823 First start and on called correctly
,# teardown
,# setup
,# Make sure stop works
,ok 824 second cleared dictionary
,2017-07-24 11:08:20 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
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
,2017-07-24 11:08:21 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
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
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'listening 60778'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F1F596ED-04EB-4CD5-AE97-B80A49545453
,[ThaliCore] Browser.startListening
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:63570569-B1AE-4581-979F-3BFBFB102A51
,2017-07-24 11:08:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
,2017-07-24 11:08:23 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"67B1214E-E287-45D1-8BEF-EBBC94C6CCB3","generation":0}]'
2017-07-24 11:08:23 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"67B1214E-E287-45D1-8BEF-EBBC94C6CCB3","generation":0}'
,2017-07-24 11:08:23 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"67B1214E-E287-45D1-8BEF-EBBC94C6CCB3","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:08:23 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"67B1214E-E287-45D1-8BEF-EBBC94C6CCB3","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-24 11:08:23 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 67B1214E-E287-45D1-8BEF-EBBC94C6CCB3 (syncValue: 8)'
,2017-07-24 11:08:23 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:63570569-B1AE-4581-979F-3BFBFB102A51:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0)
,2017-07-24 11:08:24 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"2D8CC952-620F-4C53-BCCF-6430782E2A13","generation":0}]'
2017-07-24 11:08:24 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"2D8CC952-620F-4C53-BCCF-6430782E2A13","generation":0}'
,2017-07-24 11:08:24 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"2D8CC952-620F-4C53-BCCF-6430782E2A13","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-24 11:08:24 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"2D8CC952-620F-4C53-BCCF-6430782E2A13","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Advertiser: session connected Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Advertiser: session connected Peer(uuid: "63570569-B1AE-4581-979F-3BFBFB102A51", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "67B1214E-E287-45D1-8BEF-EBBC94C6CCB3", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60782
2017-07-24 11:08:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"8","error":null,"portNumber":60782,}'
2017-07-24 11:08:26 - DEBUG thaliMobileNativeWrapper: 'Issuing multiConnect for 2D8CC952-620F-4C53-BCCF-6430782E2A13 (syncValue: 9)'
2017-07-24 11:08:26 - DEBUG thaliMobileNativeWrapper: 'Got multiConnect callback'
[ThaliCore] BrowserManager.connectT,oPeer(_:syncValue:retryCount:completion:) Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13",, generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:39 [2, 27, 33, 39]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:39
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:39
[ThaliCore] VirtualSocket.deinit vsID:39 [2, 27, 33]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:40 [2, 27, 33, 40]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:27 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:41 [2, 27, 33, 40, 41]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0 state: notConnected -> connecting
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:42 [2, 27, 33, 40, 41, 42]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:43 [2, 27, 33, 40, 41, 42, 43]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
,[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:44 [2, 27, 33, 40, 41, 42, 43, 44]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:43
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:43
,[ThaliCore] VirtualSocket.deinit vsID:43 [2, 27, 33, 40, 41, 42, 44]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:45 [2, 27, 33, 40, 41, 42, 44, 45]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:45
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:45
,[ThaliCore] VirtualSocket.deinit vsID:45 [2, 27, 33, 40, 41, 42, 44]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:46 [2, 27, 33, 40, 41, 42, 44, 46]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vsID:44
,[ThaliCore] VirtualSocket exited RunLoop vsID:44
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:44 [2, 27, 33, 40, 41, 42, 46]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
,[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:47 [2, 27, 33, 40, 41, 42, 46, 47]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:46
,[ThaliCore] VirtualSocket exited RunLoop vsID:46
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:46 [2, 27, 33, 40, 41, 42, 47]
,2017-07-24 11:08:27 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] Session.session(_:peer:didChange:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:48 [2, 27, 33, 40, 41, 42, 47, 48]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:48
[ThaliCore] VirtualSocket.closeStreams() vsID:48
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:48
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSock,etDisconnectHandler disconnecting:false
[ThaliCore] VirtualSocket.deinit vsID:48 [2, 27, 33, 40, 41, 42, 47]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:49 [2, 27, 33, 40, 41, 42, 47, 49]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:50 [2, 27, 33, 40, 41, 42, 47, 49, 50]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] Session.session(_:peer:didChange:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:51 [2, 27, 33, 40, 41, 42, 47, 49, 50, 51]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:51
[ThaliCore] VirtualSocket.closeStreams() vsID:51
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:51
,[ThaliCore] VirtualSocket.deinit vsID:51 [2, 27, 33, 40, 41, 42, 47, 49, 50]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:52 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "2D8CC952-620F-4C53-BCCF-6430782E2A13", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:60799
,2017-07-24 11:08:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9","error":null,"portNumber":60799}'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:53 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:54 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 54]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,5 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 54, 55]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 3
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:54
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:54
,[ThaliCore] VirtualSocket.deinit vsID:54 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 55]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:56 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 55, 56]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] Session.startOutputStream(with:) peer:B2196954-B48D-4FA0-8913-2BC6153108E8
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:57 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 55, 56, 57]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 4
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:55
[ThaliCore] VirtualSocket.closeStreams() vsID:55
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:55
[ThaliCore] VirtualSocket.deinit vsID:55 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 56, 57]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPCli,ent.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5,8 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 56, 57, 58]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:67B1214E-E287-45D1-8BEF-EBBC94C6CCB3:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:59 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 56, 57, 58, 59]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:60 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 56, 57, 58, 59, 60]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:4
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:4
[ThaliCore] VirtualSocket.closeStreams() vs,ID:59
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:59
,[ThaliCore] VirtualSocket.deinit vsID:59 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 56, 57, 58, 60]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
[ThaliCore] Session.startOutputStream(with:) peer:971B3C19-3E0B-4B2D-A88C-59DE77F2CE01
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:61 [2, 27, 33, 40, 41, 42, 47, 49, 50, 52, 53, 56, 57, 58, 60, 61]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,2017-07-24 11:08:30 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:3
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:3
[ThaliCore] VirtualSocket.closeStreams() vs,ID:40
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:41
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:41
[ThaliCore] VirtualSocket.deinit vsID:41 [2, 27, 33, 40, 42, 47, 49, 50, 52, 53, 56, 57, 58, 60, 61]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:42
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:42
,[ThaliCore] VirtualSocket.deinit vsID:42 [2, 27, 33, 40, 47, 49, 50, 52, 53, 56, 57, 58, 60, 61]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vs,ID:47
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:47
,[ThaliCore] VirtualSocket.deinit vsID:47 [2, 27, 33, 40, 49, 50, 52, 53, 56, 57, 58, 60, 61]
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:2D8CC952-620F-4C53-BCCF-6430782E2A13:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:62 [2, 27, 33, 40, 49, 50, 52, 53, 56, 57, 58, 60, 61, 62]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-24 11:08:30 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:52
[ThaliCore] VirtualSocket.closeStreams() vsID:52
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:58
[ThaliCore] VirtualSocket.handleEventOnInputStream endEn,countered vsID:49
,[ThaliCore] VirtualSocket.closeStreams() vsID:49
[ThaliCore] VirtualSocket.closeStreams() vsID:58
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:61
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:53
[ThaliCore] VirtualSocket.closeStreams() vsID:61
[ThaliCore] VirtualSocket.closeStreams() vsID:53
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:57
[ThaliCore] VirtualSocket.closeStreams() vsID:57
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:50
[ThaliCore] VirtualSocket.closeStreams() vsID:50
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:52
[ThaliCore] VirtualSocket.deinit vsID:52 [2, 27, 33, 40, 49, 50, 53, 56, 57, 58, 60, 61, 62]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCor,e] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:49
[ThaliCore] VirtualSocket.deinit vsID:49 [2, ,27, 33, 40, 50, 53, 56, 57, 58, 60, 61, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDis,connectHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:58
[ThaliCore] VirtualSocket.deinit vsID:58 [2, 27, 33, 40, 50, 53, 56, 57, 60, 61, 62]
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:53
[ThaliCore] VirtualSocket.deinit vsID:53 [2, 27, 33, 40, 50, 56, 57, 60, 61, 62]
[ThaliCore] VirtualSocket exited RunLoop vsID:61
,[ThaliCore] VirtualSocket.deinit vsID:61 [2, 27, 33, 40, 50, 56, 57, 60, 62]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliC,ore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:57
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:57 [2, 27, 33, 40, 50, 56, 60, 62]
,[ThaliCore] VirtualSocket exited RunLoop vsID:50
,[ThaliCore] VirtualSocket.deinit vsID:50 [2, 27, 33, 40, 56, 60, 62]
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-24 11:08:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
,2017-07-24 11:08:33 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
,2017-07-24 11:08:33 - DEBUG thaliPeerPoolDefault: 'Got err   No activity time out'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:56
,[ThaliCore] VirtualSocket exited RunLoop vsID:56
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:56 [2, 27, 33, 40, 60, 62]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
,[ThaliCore] VirtualSocket.closeStreams() vsID:60
,[ThaliCore] VirtualSocket exited RunLoop vsID:60
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:60 [2, 27, 33, 40, 62]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
,[ThaliCore] VirtualSocket.closeStreams() vsID:62
,[ThaliCore] VirtualSocket exited RunLoop vsID:62
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket.deinit vsID:62 [2, 27, 33, 40]
,2017-07-24 11:11:21 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,2017-07-24 11:11:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:11:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:11:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:12:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:12:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:13:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:13:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:14:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:14:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:15:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:15:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:16:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:16:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:17:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:17:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-24 11:18:21 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,nts plugin delay interval'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-24 11:18:21 - INFO Coordi,natedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueu,e and run in order'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-24 11,:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-24 11:18:21 - IN,F,O CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
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
,2017-07-24 11:18:21 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
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
    at SubError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95,-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/bluebird/,js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
2017-07-24 11:18:21 ,- ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-24 11:18:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,not ok 860 failed with TimeoutError
  ---
    operator: fail
  ...
,# teardown
,2017-07-24 11:18:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:18:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:18:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:19:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:19:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4,F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:20:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:20:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-24 11:21:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F9,5-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-24 11:21:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/61CC9D63-2AC2-4F95-A58D-24AD190C63B8/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
