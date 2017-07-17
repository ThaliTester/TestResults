#### Test 1271987109197780_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1271987109197780/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6s Plus 'Iphone6sPlus-1' (f70cda60583ea0f895d05ea355cd125983c27594).
,(lldb) command source -s 0 '/tmp/0EE7F7CD-E7E1-4CDD-8135-3FE251CCDC51/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/0EE7F7CD-E7E1-4CDD-8135-3FE251CCDC51/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1271987109197780/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1271987109197780/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:63211"
,(lldb)     command script import "/tmp/0EE7F7CD-E7E1-4CDD-8135-3FE251CCDC51/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
,2017-07-17 11:37:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:37:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:37:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:37:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:37:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:37:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:37:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserMa,nager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5F43B327-DAFC-4966-B580-488EBBB70752", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5F43B327-DAFC-4966-B580-488EBBB70752
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C6BBA69C-31FE-4D9E-9CDB-83479AD66463
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:5EE2CF68-4B7F-4B7E-BB32-3EED53ADC111
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "2CC2B9C2-C937-411F-87F2-1E3FDA2723DF", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:2CC2B9C2-C937-411F-87F2-1E3FDA2723DF
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:2CC2B9C2-C937-411F-87F2-1E3FDA2723DF:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "2CC2B9C2-C937-411F-87F2-1E3FDA2723DF", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-17 11:37:38 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
Total duration:  1.506193041801453
,2017-07-17 11:37:38 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
2017-07-17 11:37:38 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:2CC2B9C2-C937-411F-87F2-1E3FDA2723DF:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "2CC2B9C2-C937-411F-87F2-1E3FDA2723DF", generation: 0)
,2017-07-17 11:37:41 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-17 11:37:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-17 11:37:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-17 11:37:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-17 11:37:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-17 11:37:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-17 11:37:45 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-17 11:37:45 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-17 11:37:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:37:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:37:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:38:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:38:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:38:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:38:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:38:24 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-17 11:38:24 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-17 11:38:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
,# setup
,# closeAll with promise
,2017-07-17 11:38:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-17 11:38:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-17 11:38:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-17 11:38:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-17 11:38:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-17 11:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-17 11:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
,2017-07-17 11:38:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-17 11:38:51 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-17 11:38:52 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
,# teardown
,# setup
,# onPeerLost calls jxcore
,2017-07-17 11:38:59 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-17 11:39:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FB8175D6-0694-4987-BC41-2C20D7A601AE
[ThaliCore] Browser.startListening
2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:39:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BCAE13F3-9B1F-4047-96BB-622D13155EF5
[ThaliCore] Browser.startListening
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Can call startLis,teningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:39:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'M,ethod peerAvailabilityChanged registered to native'
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResol,v,ed registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E9ABCBC3-689F-496A-9FE1-452560395900", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E9ABCBC3-689F-496A-9FE1-452560395900
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 74 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E9ABCBC3-689F-496A-9FE1-452560395900
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "05D63F81-F64A-4AF3-94E8-3D7AB7222A9F", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:05D63F81-F64A-4AF3-94E8-3D7AB7222A9F
2017-07-17 1,1:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "05D63F81-F64A-4AF3-94E8-3D7AB7222A9F", generation: 1)
[ThaliCore] ,Advertiser.startAdvertising with peerID:05D63F81-F64A-4AF3-94E8-3D7AB7222A9F
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:05D63F81-F64A-4AF3-94E8-3D7AB7222A9F
[ThaliCore] Advertiser.stopAdvertising() peerID:05D63F81-F64A-4AF3-94E8-3D7AB7222A9F
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 81 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNon,TCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisin,gActive":false}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:39:08 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "072F8955-002F-4FB8-B690-7FD6A3751092", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:072F8955-002F-4FB8-B690-7FD6A3751092
2017-07-17 1,1:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:08 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A691E7A1-CC03-4C85-B978-B361D6957042
[Thali,Core] Browser.startListening
,2017-07-17 11:39:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:39:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:71CDA35F-9267-45B6-A828-FDA702B4717C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "71CDA35F-9267-45B6-A828-FDA702B4717C", generation: 0)
,ok 88 peers must be an array
,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:072F8955-002F-4FB8-B690-7FD6A3751092:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "072F8955-002F-4FB8-B690-7FD6A3751092", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:072F8955-002F-4FB8-B690-7FD6A3751092
2017-07-17 1,1:39:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:39:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 S,hould be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3D697D64-8E3B-41E6-AC54-F02BB2C336FA
2017-07-17 11:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:21, - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkTy,pe":null}})'
2017-07-17 11:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[Thal,iCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:ED603480-941C-456A-A3C0-F97D1C3EED1B
[ThaliCore] Browser.startListening
2017-07-17 11:39:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"adver,tisingActive":true}'
2017-07-17 11:39:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"rout,er":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
2017-07-17 11:39:22 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"613A62B9-F503-4283-BB13-6AFB671D570F","generation":0}'
2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 613A62B9-F503-4283-BB13-6AFB671D570F, (syncValue: XSqW1yquEt7cqMB3a4VPE0GyCRl6Z8ws)'
,2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4B65DE7B-3539-4B12-BB30-BD0032967742
[ThaliCore] Advertiser: session connected Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4B65DE7B-3539-4B12-BB30-BD0032967742 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
,2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6D26B543-6D86-4464-9151-F821BBB0AE6A","generation":0}'
,2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:22 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3D697D64-8E3B-41E6-AC54-F02BB2C336FA:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52293
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XSqW1yquEt7cqMB3a4VPE0GyCRl6Z8ws","error":null,"portNumber":52293}'
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'XSqW1yquEt7cqMB3a4VPE0GyCRl6Z8ws', error: 'null', listeningPort: '52293''
,2017-07-17 11:39:25 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4B65DE7B-3539-4B12-BB30-BD0032967742
,[ThaliCore] Session.session(_:peer:didChange:) peer:4B65DE7B-3539-4B12-BB30-BD0032967742 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:4B65DE7B-3539-4B12-BB30-BD0032967742 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3D697D64-8E3B-41E6-AC54-F02BB2C336FA", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4B65DE7B-3539-4B12-BB30-BD0032967742
[ThaliCore] Advert,iserRelay.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:613A62B9-F503-4283-BB13-6AFB671D570F:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisc,onnectClients() port:52293
[ThaliCore] Session.disconnect() peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "613A62B9-F503-4283-BB13-6AFB671D570F", generation: 0)
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,2017-07-17 11:39:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:3D697D64-8E3B-41E6-AC54-F02BB2C336FA
,[ThaliCore] Session.deinit peer:4B65DE7B-3539-4B12-BB30-BD0032967742
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 101 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:613A62B9-F503-4283-BB13-6AFB671D570F
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"XSqW1yquEt7cqMB3a4VPE0GyCRl6Z8ws","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"613A62B9-F503-4283-BB13-6AFB671D570F","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"613A62B9-F503-4283-BB13-6AFB671D570F","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data
,[ThaliCore] Session.deinit peer:613A62B9-F503-4283-BB13-6AFB671D570F:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72
2017-07-17 1,1:39:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:5175208D-F083-4D40-B64F-794FF141DDD1
[Thal,iCore] Browser.startListening
2017-07-17 11:39:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:39:27 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
,2017-07-17 11:39:27 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6D26B543-6D86-4464-9151-F821BBB0AE6A","generation":0}'
,2017-07-17 11:39:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 6D26B543-6D86-4464-9151-F821BBB0AE6A (syncValue: eXdmQ5eK1HY7es08mINRhul8NQGRAayt)'
,2017-07-17 11:39:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EB99FC28-FDE5-47DF-88AC-5B18CA1373EE","generation":0}'
2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:28 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6D,26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
2017-07-17 11:39:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E8D0C536-7136-43E6-A780-C955908E4A7D","generation":0}'
2017-07-17 11:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:29 - DEBUG thaliMobi,leNativeTestUtils: 'Already running test!'
2017-07-17 11:39:29 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6D,26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:6D,26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "6,D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
,[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:6D26B543-6D86-4464-9151-F821BBB0AE6A error: max retries exceeded
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"eXdmQ5eK1HY7es08mINRhul8NQGRAayt","error":"Connection could not be established","portNumber":null}'
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'eXdmQ5eK1HY7es08mINRhul8NQGRAayt', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6D26B543-6D86-4464-9151-F821BBB0AE6A","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"6D26B543-6D86-4464-9151-F821BBB0AE6A","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:31 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EB99FC28-FDE5-47DF-88AC-5B18CA1373EE (syncValue: yNRmLicm1Xp1ZHe9cIteiF2i5XSp0YKn)'
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:31 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2
[ThaliCore] Advertiser: session connected Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6D26B543-6D86-4464-9151-F821BBB0AE6A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6D26B543-6D86-4464-9151-F821BBB0AE6A", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52301
2017-07-17 11:39:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"yNRmLicm1Xp1ZHe9cIteiF2i5XSp0YKn",,"error":null,"portNumber":52301}'
2017-07-17 11:39:34 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'yNRmLicm1Xp1ZHe9cIteiF2i5XSp0YKn', error: 'null', listeningPort: '52301''
,Connecting to the localhost:52301
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
Connected to the localhost:52301
,2017-07-17 11:39:34 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-17 11:39:34 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 104 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2
,[ThaliCore] Session.session(_:peer:didChange:) peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2
[ThaliCore] Session.startOutputStream(with:) peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2 [2]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-17 11:39:35 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-07-17 11:39:35 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
,2017-07-17 11:39:35 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-07-17 11:39:35 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:2
[ThaliCore] VirtualSocket.deinit vsID:2 []
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-17 11:39:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 105 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:09DC3B5D-BE85-4C89-8D0B-68348FA2CA72
2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateN,o,nTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:EB99FC28-FDE5-47DF-88AC-5B18CA,1373EE
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52301
[ThaliCore] Session.disconnect() peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2 state: connected -> notConnected
[ThaliCore] Adv,ertiser: session notConnected Peer(uuid: "09DC3B5D-BE85-4C89-8D0B-68348FA2CA72", generation: 0)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.dis,connectNonTCPSession()
[ThaliCore] Session.disconnect() peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2
[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.deinit peer:12625EC5-6A4D-4CF0-9EAB-D40EAED969C2
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E0CF7079-E931-4613-8F13-41A68FDA7BF3
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:39:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6FE84F03-A547-4FBC-ABF4-B6EE9FBB59CE
,[ThaliCore] Browser.startListening
,2017-07-17 11:39:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-17 11:39:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
,2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"E8D0C536-7136-43E6-A780-C955908E4A7D","generation":0}'
,2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for E8D0C536-7136-43E6-A780-C955908E4A7D (syncValue: YkPyM4XEQny9DC1m2MQPuu3uPEwsle5d)'
,2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EB99FC28-FDE5-47DF-88AC-5B18CA1373EE","generation":0}'
,2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:36 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:EB99FC28-FDE5-47DF-88AC-5B18CA1373EE:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "EB99FC28-FDE5-47DF-88AC-5B18CA1373EE", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:E0CF7079-E931-4613-8F13-41A68FDA7BF3:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:523A7280-3273-4765-AF24-D29D03483576:0
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4B7E8D7E-A7F8-444B-9652-0AE90AED8376","generation":0}'
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"523A7280-3273-4765-AF24-D29D03483576","generation":0}'
,2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:37 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E8,D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E8,D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E8,D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:E8,D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "E8D0C536-7136-43E6-A780-C955908E4A7D", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:E8D0C536,-7136-43E6-A780-C955908E4A7D error: max retries exceeded
2017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YkPyM4XEQny9DC1m2MQPuu3uPEwsle5d","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YkPyM4XEQny9DC1m2MQPuu3uPEwsle5d', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"E8D0C536-7136-43E6-A780-C955908E4A7D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"E8D0C536-7136-43E6-A780-C955908E4A7D","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-17 11:39:41 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:41 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 4B7E8D7E-A7F8-444B-9652-0AE90AED8376 (syncValue: 45Hc3FI,LguVamecyUFRnOezMtsZBPtdj)'
2017-07-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: ,0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4B7E8D7E-A7F8,-444B-9652-0AE90AED8376:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:41 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:E8D0C536-7136-43E6-A780-C955908E4A7D:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B
[ThaliCore] Advertiser: session connected Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
[ThaliCore] Advertiser: session connected Peer(uuid: "E0CF7079-E931-4613-8F13-4,1A68FDA7BF3", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B state: notConnected -> connecting
[T,haliCore] Session.session(_:peer:didChange:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52312
2017-07-17 11:39:44 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"45Hc3FILguVamecyUFRnOezMtsZBPtdj","error":null,"portN,umber":52312}'
2017-07-17 11:39:44 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '45Hc3FILguVamecyUFRnOezMtsZBPtdj', error: 'null', listeningPort: '52312''
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
Connecting to the localhost:52312
,Connecting to the localhost:52312
Connecting to the localhost:52312
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[Th,aliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCo,re] Session.startOutputStream(with:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
Connected to the localhost:52312
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B
,Connected to the localhost:52312
,Connected to the localhost:52312
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [3]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
[ThaliCore] Session.startOutputStream(with:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4, [3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B
[ThaliCore] Session.startOutputStream(with:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5, [3, 4, 5]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
[ThaliCore] Session.startOutputStream(with:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [3, 4, 5, 6]
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [3, 4, 5, 6, 7]
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [3, 4, 5, 6, 7, 8]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
[ThaliCore] Session.startOutputStream(with:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [3, 4, 5, 6, 7, 8, 9]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B
[ThaliCore] Session.startOutputStream(with:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:10 [3, 4, 5, 6, 7, 8, 9, 10]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B
[ThaliCore] Session.startOutputStream(with:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:11 [3, 4, 5, 6, 7, 8, 9, 10, 11]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,ok 109 correct string length
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:3
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:3
,[ThaliCore] VirtualSocket.deinit vsID:3 [4, 5, 6, 7, 8, 9, 10, 11]
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [4, 5, 7, 8, 9, 10, 11]
,ok 112 got the same data back
,ok 113 got the same data back
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-17 11:39:44 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received all data: 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,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,vHFrpDa8f079vcy9AGU7wsPfYylwXD1WwbF6BCvUsAwm6lSQe718nPpseNPqh70L3W0MmfdjYuIoZ42qdDbHsdQtftjtB1DBOvoS9LsEHDVCrwfseR70LoDz4GMFdni8PSLQ791SmBw3D0mtrPaoxytmG2cSeJJTCRIcUdParzHijhZYGBGTyNfoFxiFTggkGHNzTFpIm0s4fALvInc0iKDAPCCAwDe7M9lfETSvpj908GoZG9HlzjkVFnVADrT8,wfmtVmigBsr2wePjaxw6HhyDPnrz1TS807jIg5mTvAEFMthPdkFyQWyzYnajYwjdOJvBAVL9AQ57Uy4UJ51ELRIRJixKfOXz2TofyF2mELqR75UKc5GRrDaqNNtVsZncRJCgzs4vKHGHOM1fzY9N9S5bNKUiCYQyvkDEntpJRvSgpGuTYWRzT8ETDJTJiVBREsp0vzAmczY7O8NssjDbsy7uGS3ryAdsrmmhj12n0rOMSLnkShmnDp1Hy6d9ylEK,Jd7lGocfo4A9CotUbAp7difuCX7B3RZzpYwCK7YYIJMSKWKotxTCc1wiSNqTUVB0K2Q9fMR6ZFxCjPQg5Jx4CgixQv3qDjriqz4PHhv1ZIxElKMA8fU4WdtUxHfmFoXSO1bX6WOmVHi4jdsHiOzfpc6Y2DGn8vwVGgxLzoZdqLI7M1QEe57MaPZQhny3jypn35Q6G40a2ietlhvgL3GRzDm6arqO6T6pmqdmyDZhpvGLEQNvcVC0dNBCLxKE57a1,OJfc5agEpeg24Z90EkSeOILpJ8EnEvHjO7lzLIPnMN825jIWmM4BzFGzFzd1N36p4uW93kGx6Hs99xNH3D030sK3sCtsRXnND87oFiRVaK0oXJmqmVPmr5EVxcggKEdUgxPJx4CzOkOLBFyYehpWdpzXc5Ux8T0zh2VGPrW4k1GdsTGd4U7H6L1vPgp87dWG7lPyqiKKPU7Zn6DCt7VNesHtLq8gf4KXOj0Y0Whrj28dS8zpgQ4M3AAZSEGVq2F4,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [5, 7, 8, 9, 10, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withErr,or:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,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'
2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:5,
[ThaliCore] VirtualSocket.closeStreams() vsID:5
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [7, 8, 9, 10, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received all data: fGvkgjLYTzUPZsKVa4Xc8n9YgdoEt9fDLrDKTcTg0t4UfzECMfIst7iVRzEFL4jmYqG7Hh5DeSJEgwLJ6hqp8hz9Nhgk2Du1ihNwboNYGMKIFTVpa763FQfkpqN3bEaX8ajS0k5LtZxa3H9EOGTbkbXLH77DsrtHRH3lVF7HxdmJLUQ6eD,PPRJlXTfe0fT0qEVPmnFD2PdSAsnZWUYDvsekz9FrqvL6cTD0vRhV7vuO7BczjpSSiuKzaPOBpA9EXasNqnJkzBkipxyaZq7nmw1dkNAfGCGxxLYcSfMlQCeIx2HqR3VoSYWXIQ5R7PfBWaRVJUJjjIPLuHnqSbFecBF3rJq6b6orCyK27XTMNjfAALDXAvaMr4quKFQaIaXRSJzNhBmcroBCA37EnO3pEZUaTIPMp2bv1Pd57kFghtaWMlmQSBw,1D2fwIgvtk9zhjgmzJbpJSWq3cZWD4CyMzgATOHbfh1DLNdR1D8eATfWmw11hXnTulm7DIDBr94OPkTxOqUh9jhJlSZqBzERS66xOd5aI3mHuTl1EQCW6YkUHn1bLerWjCLnxb7SfjLnlhmvr5dHfLa0BPGPEIYYQxlxy1BQX6AZsA5Yu9wZlOYo8HkgwPFXyzuRMDSfZsjbOzPgck4Hb80CPRxPXdh4yumLXDx74UC5IJXdkVh6LyHc1lyJzF6S,0ag5bHcWFxtaL4lumNv8mIepu3XVNwDOC3uqnyzm3uaLAbcxF13kt6cHraoU5K9aiuFIssGArEeV0fPu9grjg3jbl0DS6msioRvYFK1pMrphYku20oZ6qudQCuXGeVYlhrDah08JZZSVK5nwVBtR9KmtLRSpG2NH5fhsAaeDK7zVcZsbO4I9gYlIT61PkhBhEFL7xjN7YW5d0PO4lBl0IlDTD09yl0gjUl1KE5jKA6C1sv16ji0OfuxVekPDpTYQ,mhTTtaPHBsO6xJxue5K5sLqDMQLn9FCeQ1BASNDxCZt9kqrSo70dU3AjTabdL1RmmG51jLnDvDKLWBkxcUCnSQfrxXf5SZqtzDiX4itHg09A03PL47RiAfIJRHzximBS1Fut5IukSyV16j5crN4SjsfjId03lJz8haLN0Gn0pymBJa6d5mXZ3iPlhGpHr0e224AnOntDkBIuPAt7m7pEEdR7F05aqGVMDQT9pxIn93VHkSs0x32qn12Tu2Esu2wl,2591rzIcr17ELV8LOrSsiRbbH8Jv2ORfc3okVIORkwiu7MeFM8yKeUu8QBd4Lc08fLC2BLoYBh6nJmj9FmSzhVUZNWRidS4XSbiIGpgzmB8S2eUfwvLDMyozdFNFpwEmXIsEwcxh6PQLv7z31THUlatB5zfffZzVGlmwpS7npaT97LkjP6Kcq87lSzkQ9zFZj6060aeMHDGXlwaWhLEPph94dXx4lHk7TuJrv573y37kzq5NPRXsVTbDLO52Pvnu,BiPCdRDJdi8uTZZHKPXsOXzmOoiBZX6FkfWW8pdQfLS1QpEnGTsYIO1d068cquinqoHV4vCjc13SWrWQOMz5u9UxDD18iEkAsTsBGBjKivZCX0PATUED1CaUbYbcY8K8Adqwsm5RmR30wzEjJiVulJdLMK3avSMK1FngXYEyFa9dHBhg3Es3rqST4ULOjYtaTYVYuX1EWB7G4GYOGBtPtnXJPSLymT7T6FxOVdD0IUY3hqI9b3TEzh6cMA46ZrNq,T1OZ0xfspLeCUHuVbC6DN5hlRXbLlcb4lVG6ozFVYWQHwpljUwTDVosKqfZPpJVJYtRvcDcBd9jP0GeR684N2uLkhCJ61nhlAbCTP5eQXh3k1T8qP8TCPl8vesYnJActaZdHy17GJpZza8eblADM2W5Li2xIiuEOHgrzfw8H4POswYC2bS51lvkFD7YS2ZGw6mecpTVxTLE1j5KQO4WuON4cBZWXIM0bb4HkcbeRhHDdMlr8Vjr63KjQHIwSLThP,vXlw96hjK9BcatHWqdYJr2k65yKvVrIb0rQCqpnmFZuRXH5ZoEDxSidpwiREqYCUlnCksXxXjIH4xu6HwBJlm4SqO0LkPJ9zSQ5PMts6qnF95auefWDzDdTI5RqX81spnD4bicCo4vLay5vDON9r2uNagD72G0xc9LrInLr2VT3IIWzCokEGFY0mEtDmUrawJ24LJ0TaYEAXjV021Hn2VYVqHAIxLwA3OnW5i6b2Az5mBz2hhDk3ncGtF08NpTfI,zyYmyWadpQVjcMg4wDSX5iuhtU4WnFG0iOs2gEJUkJTEynWKfX9QLCpJN7fv6T8QVPBDTV15zw9EYH8gXqkxcrLgThZ0eTBqccJIKJPVjXqul011Z3ii2DTikCB0smW1ks4cYV63Oe76SbIxIr0C842sfsQeP0gnFU8skW1wKBfG3sbi8gQTmVUifoHu6BaSGcsdEBbAkkHpLXZEr0g0hn0sRVEcG1ajpkXsCuMVZapTR2Kv5TtDojGoRDlHiAjY,401w6gCHz8ZGW6CBuF6m6bX2lvuegNpS2u8jyVDc4pNEbBcZ4WFiyLNJjEuW1AiV2COxLxXbDCinYfTfPWpZmYEkJ6QA8dMFNX6w8lfKsSecYCoQmPTCUHkjlVmjccker0QYcScP4PMazZ4GICWB6rExxPhmtq61mDAwnuWgkjCKJ5eDp8EwGL9xzF16QaHUGXEqKOLQQXsEHaJXuz04yeGwNWV3htLM7bGOWYaE2u5nvprNFCmkz5bcBy8kbtay,lyOrpQdXb12RVXme4t9vBIUtBWaVubxRyhKIfZigbcfLOtDbifZfj97lnP0ppYbvbj1biru8xQmV1yv2a8GHh6uiZgaCJGEtAW7C59xZ6QVOKyoYPrzU9mZuxlnvoLnB5CPanISO3Dr4YahgyEDHTHfEab4vgq5ZCkMGm46kJIsntAsmBUYoeTuBwCBZHlSJ6ISNnfvpLCxX6ya9FwFydl5BBkIIoEdVQXkvyBBxNQo9ghRMbimCIGO2oUZrOqpl,3SU36kq8jyU76tvDoMy4bTIrF49BXXyNUVpG0CMJogKonEn4ilJFQZQoX2ZXwhNBUqXkNPcRL8eEtV5kOcYk8uYXATUFSIPp2v2bDa1WsGFlGDW6zsV9c9fy9IzWvbnS9ftKcPMjqXxvfdgaa1EuTt5PMWwk7QYNsc4vlQm7wCLg35NkmLloW8zLgem9kYKCMbBEjh3lpMqw0V792CxllP6Ab6H2753R29O6bixq41yRqk7MnbEpPERHn7NPVQYM,RY0I5HV2RYZuDPeVxuuXinoR2WvjBAUzkMlYoj8LodgA4eGyUD5qALVGft2MAfrxLTc4p9HmK8wYbgrRNVk9dzrRHr6NH3FU7VXHIpWOGfun4WcXFGlC6AHZyzK81Qw72BF2VGvsQdhgSkzNPkvqgvTe9FtGTHnirs5hCw5tyUorwwTkUK6gefk7uwvcELJn5I9xc5czODUrszNizB5SpiawYj5kImrpRI2FmnZtkNrCMKw2kg8Ts1ucFCH1dvfX,A1Wptje9lkrWsxjv5eOOCNmdICbXUD9Ic9pTWZVVA00Nlk1tecUwFza7c3f3jAhalFMhQnPkxAOdmWagtLBCU9doTx5l1nysBqqAnAwO3TD8nFd9tj0q5JjN1dl2IgszAVydi0xzYvzIKvNbuyDHNXyHdUZoUUQ92DNVu5a8mrgzzoXcEKfytzb9ppWULRfscOYwMoSASFvCpZbxoJjbohFOUv6LP9rL4AgW8keWHzXYIw5SfufZNcfF1cJzW01q,td9j1T4lf6bQ1W6HRiiLiCGqrgwMDuFGlwTpFmCUTDGYPSd9vmK86Jn3sRCFnYAvNBGcHndwKz00a4AMNChQqgTBE0ATCvyfTVPaC0BaLuHsEC7fkFRhZUtpVIMVNnkPdCneD7N5TYOiiuvpYdUHqsHdUQu0INZR92InbntcxZtlPBSsit5TdcW2AFCoWOrNHpfpdPD8bpwDpTCdHJqDnmij5uYeXilZKpoxxV6wtNZm3WT5FYa24fSHcxTAOXxt,zj2aerYLfWMiSMR0537sMCtps1z8fyZB7pHb2dkNlZm2hAUuk28XDG8PnispRTZirDVVtdoCONrGs1jr5cnKKyVyAFvyHZJUuwI4LJ8AaVDH5SiODtbYWlYfiGfmDRQONgETWuXpYChFF9M4oEkKAsaMb8QLge8zgyQUbqwmCSD4KGno4VvTcSeFbKn9iSt20ZorCT0OXFq1HJnWB9DuVuU6AZZS1Gqerz6biMn4CgufsDY1hizPo211ykrr5PhU,Idegs5EMPXwlz1o7CFuOpQoyilBZvKvTX6V91lPKEB4H66SVzoLqPAKgca7Fd12oI7FzxP1SS3eoVppsdxHDrmGWk3sBBZVdc3vBR69GmTrckJKqpvQjXGaKlp8t7QtD5160xxhgnaJNLuC9uGEg1cXYEGPf2DGSuxxo2pmy2ivlmKIXYlCyEqNjy4Fdfn8bz2DALrsQ4SS2qVtjtJvRGhvyUtOBXEo3N7duhLHkVe1KM5TcDQhQfhMwztfViW4m,GQ0bkTdmZ7SdrRqWEQtHQM4td69UPqdjYyyVaiaA3e69gUyJ549kdAAXW2t4zdOShCwVDQNmLCUU6t9MWuy2sp7Hkl3BSY2sjZuFXdc54rJi1Rz0sxnDtcZnSMWWyu5L2FpglvXvEeTrDNJ21zQNYxvyP1UHBAgiEXffifiDmpbaVGwhwHExPMxojP8jKnoqTxt9U6fGsLxy9Pvu7Ci4W8GVQVeKujuWcK63A0rRAeXPBDwRplVd9s41HhAYvHtZ,9B6PoJkytqZ5hFHbmhyWRXT2drHOvSsGygqzfoBooSoCbYKRGucfIavahK6faZVoZJEPeBRJr9U42JVwWPX7pjRvexF8KRYVbrhjPFY0Od8NHFqTMDBKZLjUynfSRI7Tbdhs4lfcQ98dTUvWTnWefg5SudLL3XpETzJ1Jfg6rZBS7WYPpeP597zrIc2F1zMvwmcFWxPqkZqY6J1yffDurI6QpodjnkRDbORWZNKNHK7GMNnWXrnvGAybbx4shsas,jL53g6aQRSmcGlZCWAgjsBLz9UQ5kpOkKyAqsgo7p2XoSxlIzbDD1E7SUuZCyd3uoR2rLR4C2LjsKYEtGZfhpSMcwPRjknEDX8IoUGAQQyZBrWMsxpelPWJzIx5INSd7nn5aSc7zOWv3Nd8XKMFR7gEM7L1wV5o2DpTCF8lOpapYCPzyLe5j3fQD8FfieOdLJED3vSKPURZO0dPYnninwoqhb2pd8VQUpRPblrSWavvFWHcyT6cDjMbZfJ1y3K46,rnYmhzcyvnJPODa6qLGdfiDTc4vVuKNApE0m5Co6pD9a5NbEbXc2CCjj5T374jMYh519hAtWNVbgGrbfqLHwtdkFvxBVPPikiJkM0fvpNqYLlUMkXctW1hoVRGk1oIIW944ZOOfYxpHuTo8qns3cH0dvN2B6NrQiCZZAxBDo2kl58vGMRDw9TrrGhVHRGqPdeFQOgpN4HTMAiFK2mtVl3f48EAU1mqC4g4a3FHxxxFvnDuOk9oRzoTXZg38OPgxE,Dn3lQDykhsvBruy1Uwa4NX4qNWZh4BwvnYBHAEvyNJwRhfCuswdBawHusNaCm3t7ulHp5slbnXY70vzaESWUCe48Zwk93NYwueUy1eLy5qzC41q5ddlwOPkXQlZ1RgKKMWr7ljD92wpgt3WIzfgmag8qiz0t07optCcKqTUIZdTcxA0DBBiL5Wc5FmHvaMpMwbmwzmH93ffS1KyRQ1vBhUuMeiZHlrp9QY8Zq9T8jTlXVn5HETbwBZIwvWhXah3c,CxqKwEoczIJPKX1z3RCnqFovK75OcsLDiX6RpxtgrtI4tcb1CnJ0w1k16cWUlUQb4s24kW5RF2pCHq5KXlquUBXCfrDW1rpsun0cG3yiOxYPnFvX6BHBQsVqjc3GjlBNUw9XSdsk9U37MbCd0zPujyWoNmKVnQkgYBH4ILoaUWJPuSuHtgvU4JPT9P5mIJ7Yf0tTTso9zjZmxjJZwVm0fqNMbm37UOu5r0mjB4yLHP0qyvIbCplQMtJj4KrRyFl6,IKUF3mMnbucj5hl9ysCX2fC6htb5RXeDsQ301nifmhZ1WpBy3LHmvno9OHXmhfYaTsuuYRPRLeB0S8uHvWNC2BV3n923zN4LVTTsmLOgrZk7u0ZHlSBvwF7UpUMYkwhdXJHJgxOtLO6JwfCatep2ZxewqesBchFzWgteR4r2xOrJIHOpIuJ67b6b7vt2GCaZtlZ2ZTYQbLpRcgfnnWE6tu8kk5DFXCLHWnLyAhf1ZS7KVELZ52DwuwMQrhNu4ogJjhLxUybo8MGgHJ1PZYQu4L966oS50HUAl9HtteppTbEl6Z9l6gz8HoJuWu97L5zkQzsUzrOJ1oNyXMaG3kQdDID9Q2VBDXFi0cg53MlOM3eh7qTQxr1KiEZGYn4bDCf4K5jcABi6wS9wlRWZBu0zEvCWVfXeQ8mdxwuyiOEOyOABqzsHw4cdUNfY4e33uCqcsKzb9sotLYJpumCKaVU6SnTJdEkEzD9tHwT1DjReJiDWfkIdQXObIxZu3xnIac63,jUrnnKyYuOGoyAarqgG5oiLrVNixjhwTTktPSynnCDvqfgR8jO8bDJSoa7rEWIOrYFe7mqp8DCny7noyGcOGARi068LmEBaQIByHUVGvY0TgaeymQkmy2w3VexRy0HIXsPfbVhQd5AcrEZ5MqinuxTSOEdRAozYxXlCud8uVq9lob0b0WbawgWZn6UdHJX8RRehotwvi8w8vhuIaDpYxOy6asz7JjsxLSCQtbnHJl3cMyKBq2tuSWbqw1K3UihVi,yEyLCekJO58hRfbnapHLRidX4l6TeJk5vOWWkKJEWhEhrmSl94Bi89x3U4TWYCgg1n287kVZPe3zmixLVfQyG5XgLuTo9JJGCFXc7sDUvF34IRiMf1MD9Lek8sEJJYQOrqNS0FTVU5039wz1FPzpmrAQpbyf1tp0PmA734bUdUj1ExlD7BqstnNCnOmxb6DhpEl3IL6nC1isgHppiYgSeQAsfoJkbo2ZGQwrffxFYBLkNNn0brJ4nN7Y7WXMXfPE,Ac2Kp3IpAwlnLc6tQxYfn2TTdTpcMu3JHKZ4SoAOC7fJd3fwZ274mn5DJ2BZYXcdlemFdXz0i2KCLYS4kOkyT28Rz1ETQqBNSkG9SGmLyztoLDNwEFnTL5hYC9q0K5HCsTyGcOeLQRRypPNgiYYKpEd9C31ELZwN1jRtudAgdQ6Jwq5V2aLre7biBULoCxRaQFbul3EnLHXuPYmPf8nO0nnvTmCV9IyJAXprfWLk0GuT2XEOVe8ckM5SxHIFk60f,saTQEM9XvYg1GaWGResfm0JVpC60pITjbF50dCzsNd6W4mWS7RtBFFSvGV82dETQ0wLJr28TU7AY97dSnn2R1Eco2X2wKlAmZYE4zp3QuakIofYxkKexfqNLq8bYxJgWwx7FUEz3HWzt3j53rZnOJgNhlzkbQXDhN2HmPTosG3tenwaj3yJcY8qWHjsNne4NpI1eTcqPrdmXzk2QdjTNh4dSVjxPAggrsVnDUwioceJGWKj0NVL7MPIkrqBzguOT,ILzNUxDleMIcxK3CodcsgtTC2rKqqz5rFJEmkKO0OQJZakdBZpB1vhtaJG0rO2uOLIq54FkpA2T9HYVqgtGRlyEPBw5mAnI5YIU06tl7BUfmW8CAdAaDM8XvoLGhfpMHpJRU6y0g4lGvJzhgMYEqjapevmmElb9OGuv1HR0TwDiNiiQ4lHxBXTunqQ5hQqRV19cpaf1mW4EtHkGiNuwTuz3ruRxun7HwwWFumeuLPYdRZJrUhHUCFSd1hpj8VlN9,Xckwo8JVARe27PUgskwo372GzETswIpEJMl6IKfZik5xCwTgoTqhYIHTsyZpxw1Lg3fL3aO7tyR6Wxnz1kbfBykMiXyqmdDQFxOolzFIDSHxL5py6CKJowQ7WqmGkd0e3Q1CMIzpirsXuCyZ5AU5HFf9nkS2fnIXos6MjrUzEFPfCNvvnUo5hvXVJgwH7gxQjkKP6KC5O5NxrqVSr9FFgmpoln5fG5TaNny2rOSd00O6Yfkvt07iYiD6lTAatZ2T,WbI9Y4WMyoA1QLE0lsJ36LNjABkZfJtHmO6PDutqyPw3Wqe6Zq4980R7CMy2AIPfV3lbE8xHkbs8hmwDD6DsvBOFQsaTl8Oc2sUEyVKtfNPkJL7SL7F3S26sNGJUB7TkhsWesvHNNmHI7m94kSPvW0br4tLiXXrCgQxhuZoIOUw2TFkd79Wm1eWlVPcB4oR8NqW7lum3Y41Da2xRqoOonrQJLgHXl6BqDoskez3ssMGnhyrSClTxhT0f5LC708nu,WXKMDP0ctpCIN8TUZcxx1DxBDrMDNRhSa5mMJvV7w8svVOJTdDWTqKaLqpMYENvkEqJPVcvLNNj4q6caCwCDdjk2mLcN2qEzIik8kMDsbph8dhOQCPYWNHCY6iCcF3zJuoZFR1VzVIp8QVzX2jpyMJQsSqdkALRWAkZHViBNt7TCJne9xrHybDX5yHWV7AcezaNTTl079WReWJnn8rTjfHe7A5nsDYavGy3h2nOCBzNKeOM5320Zgz61SJbtrdB0,r9M2gthsYOAhdEtaotlQfruJJoDc78G7c0MqRT9YdObSEaXqBR72DsMC7ux514PFm5lgtEyRkBZHlVxcoolD3y2YLzO95WakfvlUlUAbfnkFiYGvV0XMB8I312JFp7Nnda0v6fOHtfbBsYGasD4XENhuSXr5kLVddZTzrl5iJbB1aqWdOh5NGdZxaod0nkgVXIZMFAAhFJXhGOSOKJzUjkHmvKZwX5Xsw9p1u2NJVwM0VeIZ5b2FMmi6sxBgjY9b,90Lz1dnm7p3ZjZ1DjBL3E59ni8uytoyAXZQ21KS7Brmbcd7v3sybTfABZirqn55Liw68SpEoog54hZpZeXYeEEEiRpatQNKYWo1p0ZH4rZx6X0KrPmXToqgOmLlfdhQqZeI5FJiVdLSYx4gstOWING0UIckKWYbDrn5T8oqQVPYVrTPHJQHktcWHsh0JDyWdOTAOrhE7k9frhH6FKV3yjxx5GQfMEY6RVnEpA8Kh1psdS8krP4WmDdwIr0dBM3Cs,w3BmoVx9JM81rBq06WquBhDHTJnBXd9o4qkxyEy68igltvIRxuIK6vrtyXKLi1STS2rLRnjQ9aTZVNb6TgBL6ao8PjbCTbILaOlfpD3FmfLCymWMVcoeZuJSm3y8MPhDx2uGoaFcvkG4ZTdAA5odegXux6HTn72rHiEuCL9FkO4O58hU3dYUGBQY5VM0bCIflxxKIMq7R2vVHIfBBO12UBGqOpyCkwa9nRAJCdraeyoEumb6tqWCCOU3HItOnQaS,tPPB8vNAiOizSZAjWg2t0M3KFmNUe9VuhRr68NODdQY0WgF1QDjAKdM8PCtWPiAwQwRy94zjumXzAqwjzylYrb225WOtdFeJqXz6whqttebJQ33XHnBTOE6Ea7g4zbHEgCJLsjEiQzRwqmxqGaTdbm1BVfK2VQCA4emJMA0mkUUbV7HJ0RM1aFqvDGHjA8bFQpwLd7o3y0FRZY97qq9dFDRquEvzE1DrwlxqN23UNjwzGa8dwLguaMRMkMcGM5Kd,odo8Yu28IgTL2uBNL1s9Om8fneYT1xZkYXVJeCEQik9GYe2nwrOgW3pbPKJ98ZCHHI8YYE2vvk8cRi3lJXS4NrHoj7LnB2GnigXEU6snEgUFwR13UqZF9ODbc01uTbbCG1FXivxwLrGSi1L45dKt11Rhm2sQcvEPJWF38qQf9Hm6hjB3pheOnZrJtG6dEnlB6Pytccn063QS1SwNN6t2EH8G4Pwd1pRw1ULdIFtfOtxKf2QMKFNlELmyHAyxAwEX,tnKQIGp23VBSYL5eUWJuvIkcmRSEp5bVC2jhNcSrip143wsP8xsGsFmeDivVtuo2qQM7HRTyt7ncQMjVqOGwI0eQLZ3h6eHBCKopUmRPYBUg8hpXe4rY1DwXhtmTQ6LXXDeQbJomugxZfOvAyR2YCVWYSRQgcxQQFANEAMPw52VtzdBs6ajfp1Re6KAk8u2Anx1fGmCeYxhtxz7pqj2pTGCSjUxjNSXSdZiIrPO2GTu2Z3ufecz8FqQBswVxOV0D,Pq8sbD1PiAlnDOaETbDCesFPocxI0BM1EkSXfnqfVCYsZn4zX4kZFce7HPRGmVCgtDPZJ916xRmy70IHVcrlVfR3HM8ICXQM45K4CfVZREF4kNWb6BrnXZBafdYl64ncuML95bwi3eDsqDcKkS4dAFLoNHQM6gwc2nONWRaNew9q2tBfyqXm4SiBv4s4Kaxp3TgtS47b8zI0slklktNmFT6PuCBMS98I9fOMt6XPa82RHIsRYTfgPysiWsqu3hDe,Aa47k3rmATytuCRhTd91givmIBi46JY807KE9tdF5o7L9rJlvKTyMd6j6WF2LOZDLlwBXFo7yc5DLiCvF2Xu9JSHyFvMQW1UocJkNPPvoANXwrhAdh5b7WMbVwrlnxnyGHfRv8b8KSKPGRgpu75DgXqn2lq8YAl2y3Yab44RK2qgbaKhtwgImhFqovzavSfcj1j1p6bhBCI6JyapY0R3JN8IznNjsrGWQHoag6lG3HkpTn9sq3PsC2iQDmv1kMwS,GdU5FIc7Z0ioJpqDENlC8hZnYubypCclQtN0Ox1GAcn5WxvJj4Ms4eFTOqKa28HgLeHYXZlCqfY0cMisxHWjbF1iBejucGglsDTFMFaAfsEvxGVubXcrs5u5WJh7ZuQOLdOkGjKP6ZuZcCx3VPd9Gf3j59E4JtOdpYuHb5ERAddl09iqZQsIsGvwZAW1IpJelBPyLy6lbNqPAqwUy1WINV1rJAMTlgxMrBdwZVORw4QCqtI0dU5qzGvUDK7GswHo,bnThSwER5kDmPXb604up4MAxle3zbsg6ShfIbUjzOybIeBL110TYAahsWspSR1n5ez40e8n00mvFewoOTIzvgo84tHM3u8HTXJG73gwD8M8zphqef7F4BuIJ1PzpdL3gvaRKdiGi5ko5zZW5MoNgb5oQRDcgW8LIefP1n3Um41ze84rIYp7SGtUDqXVwXE27Wut9BvQAIL5oT6OuCNL5ZHoUA5gXxv75346dlyqPTUHbvV3Z0nRzxivVjHph8cCj,7jezlBNAfZqdyRJUIODLLrF7mRu2CLpmCNK6C6ZVLAcbL58WYrk4PG2e8Gm3IWsVvq5GpTYF1VT1xFIQftgyFDIgi6iomUmsX50Kayi2J8MhjCcXfgOh1MeXFFokwbwkB9RJFNyH0kprt07iH6xDxoHuqCsfJxYdUQvdSuHjdIRWsSGgpt546X46nwtCoN2P030Io1ZGerpgWCwxHHUfPraFKs5JULNBOCoRvLkxgNg5olLmT4U36OUbqf7WzUXb,W2WMQSIic42bPvD9wqMGg1y0cXDTr7ErjkANu8jNmInaMZuA98EASR6ZjGkAbUNFIrGv9Ih8zYFpsaO3ylX0BHIuZGZegW7hrzMGlAugVClreHlWxqzzfU68YJWAoPQFSuPjOdPc7GQEDFq19C6iFkJFhZG4MGk3S3GpoR2D39DiS6pJbw6ZEenr0uByfHv0vELv3Qg7PdaPjOZH8MnGSK0hII0OkX3WAvQFtooYeMXSvK4vM1WHRTRWBsNTwFY1,VWGcr9wEHu64Tqw0y3TzCuiBCSb37CqvrxAsLN5KoKLgZ1AXwjY4roP9W4aY2FeXgsWPTALPCzaPuM4khoMRAbK21UBObPQtzmfGsPBDt29xAsEWlLGtLLXNWrFo2iMuI0r7HvVCpxrBqN4THePLKw2EKFWtvj9MQoWUMIQrDOEPpsIxo4Wicw1VtPN0Li6CIiCYRDBKY5KIu7FiEA9HH1emHiouEYcCbQscpocKswrmeE5VBVF3bRqfYGycfCSS,4aQEgF8NjXfcb9icOAWN7ALHVF30e3l7i1sOnMrNuUHoANtrD8oAXVDm1TL9oH83VY2G3pP00EMw4WlyS0iXqoVFF0t1TkIkksFL4LnUw89QBcocIiSTzERMgjmoPb3oNTKpBZLNJc48aoyzTppyCRljxkhj2laqsm4ItAEhQ1OqolRV2yUYwyOZOTXpq9cIhhmUEofksv7vrHmmaeZHODVUdXxgV1f4puzYaukvWhGeRUKO1xwcnRgb2XNNV4vx,Rpy6uC5E3fnAxGitGMqHpY6flrXXFofwEO7AnTWj19HLwSw77pVZ957or0u1A7nDwqubhdVFcEduwLleD03sFb9aZHluhUjH0B1vYPqUkbEHg2eySGdbWOrXhRAqsG9o9f1gQEvlkl1umN7DcPLWMrATwXimEQk1iEgD3yoUkid0llAgmmBCAsyZwbMfmd2hqZVpl0fr7QU1CJEMUYv8cAebXdZrdkiVF6ju8C3ppF8Y3bh3DrSYGQDTXwYayKRW,opkqOmsbzUq6KyeLAcNMhqcpBKh8FmDxUT45dTTGWeCl82aNy2AhpByiE7XycwzSFlPsnonhg82VV5DEIhqdewRUQpwIO31AVhAE3Epja82hirvPngHcwuO8pNp4AC03ylVLyYTSaeA5vlVxXmrxr8UPg7iCILz6INeAK5HjOuKuD4g7HNbyQekE1JTdzcc2snviSq9rw0UBYj5TL5CTPFPWR0I32hIbHwaT4iYLEMUwVz0JMxugZrUot1UHUMWG,0b4P9p5R7T7grLu2C3Mj97tsE4AcUnX0SzIHmYu16sTHDq9ngv4yeeH60jLvdjJ5DBEIb9CUfA2hhXfgR5zZiwfdwvihBdJbc0WeOZ26cb96HFNVvEbJfnYQsSfGvc5QX8qkESepFXOir6DxEGLhelXVVsCmCEvfR5bhjtF5oyB6TomVf45xupniZNwvf07OaqtBzrXeWUPzSKam5taCjtTDud9tGdIZSbYMCMeBC4u0ZCWKHo4XKEB8uuxNIzpk,CvI2iRR5VKTkQVlZKnHncuUX8VgjO7kgSajUaQr2y3u2qKoE9CXLhmP2o0oDhVpD270TuKBIiT1Djkxs54e0k1edRMeVU3HI4Scvi3U0QCSEFVVkdmvxlOWB8XhnJqHWMsigKy54wdjkaTpatGBt2e3hbZ4Dc2Rlu9vemmlcbhnCjHE5smHFkTEFyOphiRmylNh9SMXs1lD3WOOnVyEY7o6OXIHDSdbm9hkh3sC7yF5cBec6AA0rAfpXDjqc7dGO,mHmH0ArxM0ONVxRjDwaduM2sM3Pjbklk1JT9KY3Hd7YIkyvqGJXUzUK7F19DZPUrC1YZ1SrLUPjhCIozdvwcpnuXDqnFtWTVqv4cOgP9wikJXCAsC8MpVPvyVA0wPX3AD9bWbVW36sLIBnMxnfrMBkzAwv3xCrUj0UcLsDKKa2PZ8OjlWCrcitrMNsOuummPY50ZVWbPBUjGh9zBCiYvxzthQxT50wx9kUHJUaiqL4UOyFJ9QncCtmWQa6L1JocK,yBsRWD4H2WPjGbnGJVR2CggWcm5ImUpmhrl47QWzqfUd1pDsmaVZJMTB7QoVsG2l1iMlNHIkeMlWHC0yDj7oOW2Vy7FSmTPrK8uKFfix3b7KvxvZuokpbKp6Dk8p4YV4HFO1WKRbY4JrFJowkNuOk6Ohtr5nXVMbgqxFJOsTNy2Oyhg4S1hPJ7Pkc5f4UvyttU2Ng4wnTOpngi9tSaBCkzh0Exh5I4vw5OyiOJ74Qzh7l2PsKmNMYhYu9z9FqWjs,o0GoCIxubbDiFtjZIeDzjR9wgOovI0oTjqa4e2FzuW58yuxwW3dMvLrWkuifm4DklIzkesw2KycJlWtz1rOz1i3hfxMNa6LFoNqoMHtex1TLdOOdippOnxa7bsJOkm5kIJ4nZtLhSxs8lVJX4HYhGgLS2XNKfohPI2p1lTVjkNQN8ibbX0KHjFu08qVZu0LtHSoevQKHNx0O99qAgmxiYJy0gXg0eCrwIu8JmSOgNnB4nyMV4WdPhFoQdVqMkiQv,R9deaFNszc388ZYFtzajwKUO0Lc88LVanJO0apJambPRJ3abKeKkTcpvTqjryScBFsGQRh7sQcknjJBUVPQzooM28fIjpJFpsbQN9o61olCCYwGIMlShp0460qoOSFoScWpzheUSY33WD3AVBxIoGifD11nYhBoB9PEoHmqFNNIhu10phNOXC2pKfjQX507zu7uAhXlWhJsa1bSqzuIYEY71EYBGj5lEohRS6Rr82QJhxQfelIRoknVEmhLKa7CU,M2liFeG19dOlDTp11JHFY3cNULSwZXJFHdhV0f4p5Z2AUQnosINf4UwRcXtwJnjpvSs4zP2OVqBgeFeKBshZcf69InY0oHFF3sTlEpOdOXUFTIXycWdkUmZT7C73s30NxpMCLTmu85ZOqOFFWwDsZWn0VX6FiDhXZDXkgJUmMcLpUHkOj74qt8UmnDQHkDHuPVfwfotDKZI3JXAHjJXenkth6IlTspmV5H30AhYAqO1pqRV8sqKp44fSN275y51d,8ZzXlC1V6cF3SvhvkMXnfnW40UB4LcROKkoXx97ama0fu2KROAsGXo7JzbCVFhzfceVcrZfpC4yi8u5UsdzTvUixBehsB1XGKEGgYsHTey3NluAC939Y2KlsJPHn6Sq0sd1GrDTyP9zFsIqroREXED0IDHuNfyZ05oGVTe0UgzVnNefgOYZPkxRFdvxC7k9u8sVIq95lliYlgNPvqex0rPBHWR7FJYyFhsZTuzY9XkwBz8ghqO3bwYqtYMzDNK7N,6hfgVZiHbVjgSTxWyk7GlH00ihWyP6llFndBAEKpqnlIa23SiMgOtJCjyBsX4nRlzLyQVDFdld2d9AllkuvSEusNqzca2lCgnpPiHdy8v4sVgR6HPxGcqP4QVaMYh9FuslyLo8GpoXPcLcFYBa9LJVPGnh0guMjoPlKIiJhIHozdLkuMAtThVoVZDVRr5qHQQwoG2V03dudopSpVZM2vEO1qBWLkibpp1KvQ04xhHBVaGqSFiRiE1LYlnTtPxE6O,9IbJHmHtJfkHYqrKdJ2B9cVQHYAWBAew5CTXuV5P9ASfxux6CmP6R6PAKpjel6XnvSgeupUav3nx0O26YnGND6vNbV0OZZQRszLmXDecSLAUKfghCYW3U5qP7bwgy7LUd0tymluEOVwQsgcCjDlkxcn9sGiJWLzVUfiPmomCzM4hMkrQu3SjKdrQnrC9RydCe3XmbMaHuOKG4IbbJJIWpAcSb18yYHSaqv6UqnKDI2m7Cl8prOHJsFsTwZn8nsot,W9UB1mzgoMmoMO76jAUTyAVQrTygGnwfLza3KN2vch8JZca8cFYBFNAJDuwnEQXS5RheRwgoTGP6l8yC06u8mCOIYpkAae1AtfAkNrMCm6gbltCwxBBOXtyyXuLgs8cZaKRtWgYwupsLVkBUA7WaFs8MlW5ssc1ovDRC5pVvDk63FRjZUKg3TrTRvjkJpCWei2s2O4S7XBcHq3xylUNgP86ecjja4mfEcrPkblL3pyqiWpUtINXXBIjL9O8tP7D0,krZBmvQ7gjFRVtWyoy10hsJYW4d9hIpzfoAf26dfbTysua2wyWPTUiZAuvDHgc1Wlgasnd3WeiHGeKVQapewzOSsPL6C2Wd8QMqJueLFGKEtyjbd7YbTYXCjBDzri7OdYK0JZPgMskjIJGnQMo5nCpiuYHdizZNXpMnMHqdJC7bByp7Wbu2te6nHaLIBN2k2PCqEquNqIdaVmfV9KMHIZIiFUWk9M1pNU6oONX2YpfCmUi5SNKaCjHcHdyI5zdRD,QLGvvW40ni1PHTiUh75NiJ3HPlgy0fVkU4MoEWb4SWI0gNNcggRYvrUUeesPGIXRpo0JNDOVpbCJ0tsKRXYMjqMGJP6XZSKDy9mDVsWIsLSLZjJ6o0CjMPQVmALyDcbHl8xLIeyZfSCvBzY3xcZII1Q7RUZ1bF1epN9tc6n3ra9r6K5dTQi30nrz0fIdB1wtclLlSuHzLXHnKuPSS10cmcxICuhHJE99hEsZG9aKCJRIVusUEDk4qBXaiOibrFIt,OImu7fTduftgnG0tIeRA40duK2BQOg28qZ6R0xDUq2yTwcYbt6lZWB7ScDwZyd8MUZmlHJnfWGoyl85PDG8d4Nt1I8qItaGdrgVyK22C4rbhWOzh4EllGcdGhbUrRo7yHxtgimLWHME3NqtP8OjpOFcCQxLy7fY3izqnVTG1cnra3TLNcuQbpDEOr5mlzJImY9MhU1hO6RQkfOt1MDM8RKTLd9MjIfN9o7A5wJX2Q0JLvpqQo4U8F80hCDDHttij,ncQdeSS2UrmZPyhfVqaIQE1CAlDhXJB7RUxHbWTDpfqz5YqSoPiSZlNewKeo4raGScADxyVRZl79BL'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:8
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStr,eamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandl,er disconnecting:false
2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received all data: 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'
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:9
[ThaliCore] VirtualSocket.closeStreams() vsID:9
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStr,eamsHandler disconnecting:false
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandl,er disconnecting:false
2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-17 11:39:45 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [8, 9, 10, 11]
,ok 114 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:10
[ThaliCore] VirtualSocket.closeStreams() vsID:10
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:10
[ThaliCore] VirtualSocket.deinit vsID:10 [8, 9, 11]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) cli,ent disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:11
[ThaliCore] VirtualSocket.closeStreams() vsID:11
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:11
[ThaliCore] VirtualSocket.deinit vsID:11 [8, 9]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocke,tDisconnectHandler disconnecting:false
,# teardown
,2017-07-17 11:39:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [8]
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:E0CF7079-E931-4613-8F13-41A68FDA7BF3
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52312
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
[ThaliCore] AdvertiserRelay.deinit
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"45Hc3FILguVamecyUFRnOezMtsZBPtdj","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4B7E8D7E-A7F8-444B-9652-0AE90AED8376","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"4B7E8D7E-A7F8-444B-9652-0AE90AED8376","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:03AC233D-6CE2-4760-BA65-38CFD843635B state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E0CF7079-E931-4613-8F13-41A68FDA7BF3", generation: 0)
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "15599E72-C57A-4218-B314-C9C3FB7E4346", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:15599E72-C57A-4218-B314-C9C3FB7E4346
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:613BA8C1-C1B8-46B6-BDAB-373632FE1402
,[ThaliCore] Browser.startListening
,2017-07-17 11:39:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-17 11:39:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Session.deinit peer:0DADBCFB-6B0A-4018-943C-1F6F4172E508
,[ThaliCore] Session.deinit peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
2017-07-17 11:39:46 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"523A7280-3273-4765-AF24-D29D03483576","generation":0}'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 523A7280-3273-4765-AF24-D29D03483576, (syncValue: QwyKGdHAJPvw7E7nuQz6x4ay5eFgctet)'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "523A7280-3273-4765-AF24-D29D034,83576", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
,2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"4B7E8D7E-A7F8-444B-9652-0AE90AED8376","generation":0}'
,2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:46 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:4B7E8D7E-A7F8-444B-9652-0AE90AED8376:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "4B7E8D7E-A7F8-444B-9652-0AE90AED8376", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscov,eryInfo:) found peer:58491740-8F67-4D72-A396-FDAC62354394:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:15599E72-C57A-4218-B314-C9C3FB7E4346:0
2017-07-17 11:39:47 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58491740-8F67-4D72-A396-FDAC62354394","generation":0}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "15599E72-C57A-4218-B314-C9C3FB7E4346", generation: 0)
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","generation":0}'
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:47 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:523A7280-3273-4765-AF24-D29D03483576:0 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:523A7280-3273-4765-AF24-D29D03483576:0
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:523A7280-3273-4765-AF24-D29D03483576:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,3A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,23A7280-3273-4765-AF24-D29D03483576", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:523A7280-3273-4765-AF24-D29D03483576:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:523A7280-3273-4765-AF24-D29D03483576:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,3A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,23A7280-3273-4765-AF24-D29D03483576", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:523A7280-3273-4765-AF24-D29D03483576:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:52,3A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:523A7280,-3273-4765-AF24-D29D03483576 error: max retries exceeded
2017-07-17 11:39:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QwyKGdHAJPvw7E7nuQz6x4ay5eFgctet","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:39:51 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'QwyKGdHAJPvw7E7nuQz6x4ay5eFgctet', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:39:51 - DEBUG thaliMobileNativeWrapper: 'Received, peer availability changed event with {"peerIdentifier":"523A7280-3273-4765-AF24-D29D03483576","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:39:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEven,t due to not being in started state'
2017-07-17 11:39:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"523A7280-3273-4765-AF24-D29D03483576","peerAvailable":true,"portNumber":null,"recreated":true}'
2,017-07-17 11:39:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-17 11:39:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 58491740-8F67-4D72-A396-FDAC62354394 (syncValue: 3ILsMeX,pkmq1yIpc7AC4XQEdpZ5wTF53)'
2017-07-17 11:39:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:58491740-8F67-4D72-A396-FDAC62354394:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:39:51 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:58491740-8F67-4D72-A396-FDAC62354394:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:523A7280-3273-4765-AF24-D29D03483576:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "523A7280-3273-4765-AF24-D29D03483576", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:58491740-8F67-4D72-A396-FDAC62354394:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:58491740-8F67-4D72-A396-FDAC62354394:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52338
2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"3ILsMeXpkmq1yIpc7AC4XQEdpZ5wTF53",,"error":null,"portNumber":52338}'
2017-07-17 11:39:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '3ILsMeXpkmq1yIpc7AC4XQEdpZ5wTF53', error: 'null', listeningPort: '52338''
,Connecting to the localhost:52338
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:58491740-8F67-4D72-A396-FDAC62354394:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:58491740-8F67-4D72-A396-FDAC62354394:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:12 [8, 12]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:52338
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-17 11:39:54 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:12
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:12
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,# teardown
,2017-07-17 11:39:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:15599E72-C57A-4218-B314-C9C3FB7E4346
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:58491740-8F67-4D72-A396-FDAC62354394
,[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52338
[ThaliCore] Session.disconnect() peer:58491740-8F67-4D72-A396-FDAC62354394:0
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:58491740-8F67-4D72-A396-FDAC62354394:0
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:39:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:39:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "09BB567D-7B1E-4093-B10E-64E73CF5C4BE", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:09BB567D-7B1E-4093-B10E-64E73CF5C4BE
2017-07-17 11:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:39:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:CAC20A51-C0E4-43E0-9E0C-6E8B9B3113FF
,[ThaliCore] Browser.startListening
,2017-07-17 11:39:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:39:55 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:39:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
2017-07-17 11:39:56 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"58491740-8F67-4D72-A396-FDAC62354394","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 58491740-8F67-4D72-A396-FDAC62354394 (syncValue: NzklXiiv8EtfEzQZ,jxQE5jNHbYm5udCv)'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0) creating a new relay
[Tha,liCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","generation":0}'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:09BB567D-7B1E-4093-B10E-64E73CF5C4BE:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "09BB567D-7B1E-4093-B10E-64E73CF5C4BE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FA8589D-0E52-4FB5-86A3-8C265869ADC1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FA8589D-0E52-4FB5-86A3-8C265869ADC1", generation: 0)
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5FA8589D-0E52-4FB5-86A3-8C265869ADC1","generation":0}'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:39:56 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:58491740-8F67-4D72-A396-FDAC62354394:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:58,491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "5,8491740-8F67-4D72-A396-FDAC62354394", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:58491740-8F67-4D72-A396-FDAC62354394:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:58491740-8F67-4D72-A396-FDAC62354394:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "58491740-8F67-4D72-A396-FDAC62354394", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "58,491740-8F67-4D72-A396-FDAC62354394", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-17 11:39:58 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"NzklXiiv8EtfEzQZjxQE5jNHbYm5udCv","error":"Peer is unavailable",,"portNumber":null}'
2017-07-17 11:39:58 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'NzklXiiv8EtfEzQZjxQE5jNHbYm5udCv', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-17 11:39:58 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"58491740-8F67-4D72-A396-FDAC62354394","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:39:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-17 11:39:58 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"58491740-8F67-4D72-A396-FDAC62354394","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-17 11:39:58 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:39:58 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-17 11:39:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09 (syncValue: tAkK04g07uzIdzJLzqQniaz,zYW6MUgU2)'
2017-07-17 11:39:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED,19C9C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:39:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-17 11:39:58 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EC,3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,C3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EC,3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,C3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:97049D03-FF8B-4917-87CA-E5C43D1A8355
[ThaliCore] Session.session(_:peer:didChange:) peer:97049D03-FF8B-4917-87CA-E5C43D1A8355 state: notConnected -> connecting
[ThaliCore] Advertis,er: session connected Peer(uuid: "09BB567D-7B1E-4093-B10E-64E73CF5C4BE", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EC,3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "E,C3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:EC,3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:EC3577AD,-9A13-49A1-BBEA-3F4ED19C9C09 error: max retries exceeded
2017-07-17 11:40:02 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"tAkK04g07uzIdzJLzqQniazzYW6MUgU2","error":"Connection could not be established","portNumber":null}'
,2017-07-17 11:40:02 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'tAkK04g07uzIdzJLzqQniazzYW6MUgU2', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-17 11:40:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:02 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:02 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:02 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-17 11:40:02 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 8763C22E-349D-4875-B6BD-8F71D8CD3697 (syncValue: 09fkSCndq2Ah4eLgEgK9sCd7vdsgnfMF)'
,2017-07-17 11:40:02 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:40:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:02 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.deinit peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:97049D03-FF8B-4917-87CA-E5C43D1A8355
,[ThaliCore] Session.session(_:peer:didChange:) peer:97049D03-FF8B-4917-87CA-E5C43D1A8355 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:97049D03-FF8B-4917-87CA-E5C43D1A8355
[ThaliCore] Session.startOutputStream(with:) peer:97049D03-FF8B-4917-87CA-E5C43D1A8355
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:13 [8, 12, 13]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (3285 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1166 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017,-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (2190 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (5475 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (1024 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (13312 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received (19445 bytes):'
,2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server sends data back to client (65536 bytes):'
2017-07-17 11:40:03 - DEBUG testThaliMobileNative: 'Server data flushed',
[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:13
[ThaliCore] VirtualSocket.closeStreams() vsID:13
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID,:13
[ThaliCore] VirtualSocket.deinit vsID:13 [8, 12]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.di,dSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52360
,2017-07-17 11:40:05 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"09fkSCndq2Ah4eLgEgK9sCd7vdsgnfMF","error":null,"portNumber":52360}'
,2017-07-17 11:40:05 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '09fkSCndq2Ah4eLgEgK9sCd7vdsgnfMF', error: 'null', listeningPort: '52360''
,Connecting to the localhost:52360
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,Connected to the localhost:52360
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:14 [8, 12, 14]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-17 11:40:05 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:14
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:connected
,ok 124 got the same data back
,# teardown
,2017-07-17 11:40:06 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:09BB567D-7B1E-4093-B10E-64E73CF5C4BE
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:8763C22E-349D-4875-B6BD-8F71D8CD3697
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectio,nsAndDisconnectClients() port:52360
[ThaliCore] Session.disconnect() peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:97049D03-FF8B-4917-87CA-E5C43D1A8355 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "09BB567D-7B1E-4093-B10E-64E73CF5C4BE", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:97049D03-FF8B-4917-87CA-E5C43D1A8355
[ThaliCore] Advert,iserRelay.deinit
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:97049D03-FF8B-4917-87CA-E5C43D1A8355
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3511E93B-4194-4DF4-9D01-81A79994D342
[ThaliCore] Browser.startListening
2017-07-17 11:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 127 We should start listening fine
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C22ED207-1690-4275-814E-7C3ED1327DC2", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C22ED207-1690-4275-814E-7C3ED1327DC2
2017-07-17 1,1:40:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:40:07 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-17 11:40:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 128 We should start updating fine
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09", generation: 0)
2017-07-17 11:40:08 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}]'
,2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}'
2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Filt,ered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"EC3577AD-9A13-49A1-BBEA,-3F4ED19C9C09","generation":0}]'
,2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"EC3577AD-9A13-49A1-BBEA-3F4ED19C9C09","generation":0}'
,2017-07-17 11:40:08 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C22ED207-1690-4275-814E-7C3ED1327DC2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C22ED207-1690-4275-814E-7C3ED1327DC2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D0E56831-394E-47D9-BA4F-82F9ECB0DA87:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D0E56831-394E-47D9-BA4F-82F9ECB0DA87", generation: 0)
2017-07-17 11:40:09 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"D0E56831-394E-47D9-BA4F-82F9ECB0DA87","generation":0}]'
2017-07-17 11:40:09 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"D0E56831-394E-47D9-BA4F-82F9ECB0DA87","generation":0}'
2017-07-17 11:40:09 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:8763C22E-349D-4875-B6BD-8F71D8CD3697:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "8763C22E-349D-4875-B6BD-8F71D8CD3697", generation: 0)
2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}]'
2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"8763C22E-349D-4875-B6BD-8F71D8CD3697","generation":0}'
2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:40:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C22ED207-1690-4275-814E-7C3ED1327DC2
2017-07-17 ,11:40:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130, ,Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Test updating advertising and parallel data transfer
,2017-07-17 11:40:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:14 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in tea,rdown
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BA950FFE-9575-4615-AE41-B4F4A01E629B
,[ThaliCore] Browser.startListening
,ok 133 discoveryActive should be false
,ok 134 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "75B95731-9AA2-4083-B5AA-BAC472AF7EBB", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:75B95731-9AA2-4083-B5AA-BAC472AF7EBB
,ok 135 discoveryActive should be false
ok 136 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
ok 137 discoveryActive should be false
,ok 138 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:75B95731-9AA2-4083-B5AA-BAC472AF7EBB
,ok 139 discoveryActive should be false
,ok 140 advertisingActive should be true
,ok 141 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 142 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 143 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-17 11:40:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:15 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 145 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-17 11:40:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-17 11:40:16 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 148 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-17 11:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-17 11:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:17 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 153 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-17 11:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 154 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call multiConnect when start listening for advertisements is not active
,ok 156 Got null as expected
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:e20f10e4-b306-47c9-ab3a-74007dc12e53 error: startListeningNotActive
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved:, {"syncValue":"aTkqSdxk1K6Q6vuJQnDhdeAgppnp6q6u","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 157 Should only get called after multiConnect returned
ok 158 SyncValue matches
,ok 159 Got right error
ok 160 listeningPort is null
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"e20f10e4-b306-47c9-ab3a-74007dc12e53","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"e20f10e4-b306-47c9-ab3a-74007dc12e53","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 161 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 162 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3FDC400D-F955-45F8-B458-58EB357AF223
,[ThaliCore] Browser.startListening
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 163 No error on starting
,ok 164 Got null as expected
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"hXcNqzXdAyQfgfIgkG2faWkRoo54UHGU","error":"Illegal peerID","portNumber":null}'
,ok 165 Should only get called after multiConnect returned
,ok 166 SyncValue matches
,ok 167 Got right error
,ok 168 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 169 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisi,ngActive":false}'
2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 170 Should be able to call stopAdvertisingAndListening in teardown
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: ,'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectRes,o,lved registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# multiConnect properly fails on legal but non-existent peerID
,2017-07-17 11:40:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'multiConnect properly fails on legal but non-existent peerID''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 172 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call multiConnect with invalid syncValue
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:6892A8F9-546D-404F-ADD8-296BFEEF70C4
[ThaliCore] Browser.startListening
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":fal,se,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 173 No error on star,ting
ok 174 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 175 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 176 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# cannot call disconnect with invalid peer id
,ok 177 Got right error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:40:19 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 178 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 179 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
,[ThaliCore] BrowserManager.disconnect peer:e3eddf3d-6f0c-48ac-9a79-202fa748f349
,ok 180 No error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 181 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:40:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 182 Should be able to call stopAdvertisingAndListening in teardown
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Get same port when trying to connect multiple times on iOS
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:3227DF1D-62DA-41B7-BCBA-445AE86618B2
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:40:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:40:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 183 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:02E46E65-5DF2-473F-A3F7-4C3E32C1CD9C
,[ThaliCore] Browser.startListening
,2017-07-17 11:40:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:40:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:40:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 184 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3227DF1D-62DA-41B7-BCBA-445AE86618B2:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
2017-07-17 11:40:21 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3C2C6DFD-3481-46B7-BF2E-3B8B8326D366","generation":0}'
2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3C2C6DFD-3481-46B7-BF2E-3B8B8326D366, (syncValue: esm25yeg47Anl1ZZhYKnQLtRbk8ILxw9)'
2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B832,6D366", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6396697D-E678-496B-A513-1569FA649E5E:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6396697D-E678-496B-A513-1569FA649E5E", generation: 0)
,2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"6396697D-E678-496B-A513-1569FA649E5E","generation":0}'
2017-07-17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
2017-07-,17 11:40:21 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52367
,2017-07-17 11:40:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"esm25yeg47Anl1ZZhYKnQLtRbk8ILxw9","error":null,"portNumber":52367}'
,2017-07-17 11:40:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'esm25yeg47Anl1ZZhYKnQLtRbk8ILxw9', error: 'null', listeningPort: '52367''
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
,ok 185 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0) found active relay
,2017-07-17 11:40:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"SMTgBfkUMjD1kHSLIKpbO8qzRkCmRyCY","error":null,"portNumber":52367}'
,ok 186 No error
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:15 [8, 12, 14, 15]
ok 187 Ports equal
[ThaliCore] BrowserRelay.didOpenVirtualSocketSt,reamsHandler
,ok 188 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0) found active relay
,2017-07-17 11:40:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"QkxLpRUPNYAiK2dVxwFJF0xJmJkRcI8S","error":null,"portNumber":52367}'
,ok 189 No error
,ok 190 Ports equal
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:C09065A6-0F62-42D6-9222-BDBE3A9BDF26
[ThaliCore] Advertiser: session connected Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:C09065A6-0F62-42D6-9222-BDBE3A9BDF26 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:4849B908-940A-4C79-8626-203B01FEA846
[ThaliCore] Advertiser: session connected Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:4849B908-940A-4C79-8626-203B01FEA846 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:4849B908-940A-4C79-8626-203B01FEA846
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:C09065A6-0F62-42D6-9222-BDBE3A9BDF26
,[ThaliCore] Session.session(_:peer:didChange:) peer:C09065A6-0F62-42D6-9222-BDBE3A9BDF26 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:C09065A6-0F62-42D6-9222-BDBE3A9BDF26
[ThaliCore] Session.startOutputStream(with:) peer:C09065A6-0F62-42D6-9222-BDBE3A9BDF26
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:16 [8, 12, 14, 15, 16]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:peer:didChange:) peer:4849B908-940A-4C79-8626-203B01FEA846 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:4849B908-940A-4C79-8626-203B01FEA846
,[ThaliCore] Session.startOutputStream(with:) peer:4849B908-940A-4C79-8626-203B01FEA846
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:17 [8, 12, 14, 15, 16, 17]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-17 11:40:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:40:29 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 191 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:3227DF1D-62DA-41B7-BCBA-445AE86618B2
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:16
[ThaliCore] VirtualSocket.closeS,treams() vsID:16
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:16
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error, Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisco,nnectHandler disconnecting:false
,[ThaliCore] VirtualSocket.deinit vsID:16 [8, 12, 14, 15, 17]
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:17
[ThaliCore] VirtualSocket.closeStreams() vsID:17
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsH,andler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:17
[ThaliCore] VirtualSocket.deinit vsID:17 [8, 12, 14, 15]
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:4849B908-940A-4C79-8626-203B01FEA846 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:4849B908-940A-4C79-8626-203B01FEA846
,2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 192 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52367
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:15
,[ThaliCore] VirtualSocket exited RunLoop vsID:15
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:15 [8, 12, 14]
,[ThaliCore] Session.disconnect() peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:disconnecting
[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:C09065A6-0F62-42D6-9222-BDBE3A9BDF26 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "3227DF1D-62DA-41B7-BCBA-445AE86618B2", generation: 0)
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"esm25yeg47Anl1ZZhYKnQLtRbk8ILxw9","error":"Session disconnected","portNumber":null}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3C2C6DFD-3481-46B7-BF2E-3B8B8326D366","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3C2C6DFD-3481-46B7-BF2E-3B8B8326D366","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,[ThaliCore] Session.deinit peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] AdvertiserRelay.deinit
,[ThaliCore] Session.deinit peer:4849B908-940A-4C79-8626-203B01FEA846
,# initial peer discovery
,2017-07-17 11:40:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:29 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 1
,2017-07-17 11:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
,# teardown
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# update peer discovery 2
,2017-07-17 11:40:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# check latest peer discovery
,2017-07-17 11:40:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Set up for no peer discovery test
,2017-07-17 11:40:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:31 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# no peer discovery
,2017-07-17 11:40:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# calling createNativeListener directly rejects
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'listening 52372'
,ok 193 Should throw
,# teardown
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits incomingConnectionState
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'listening 52374'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 194 initial connection state should be CONNECTED
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 195 final connection state should be DISCONNECTED
,# teardown
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# emits routerPortConnectionFailed
,2017-07-17 11:40:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'listening 52377'
,2017-07-17 11:40:32 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:32 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 196 tried to connect to right port
,ok 197 failed due to refused connection
,ok 198 routerPortConnectionFailed is emitted
,# teardown
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'incoming ,- incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server connections all up
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'listening 52381'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 199 Send/recvd #1 should be equal length
,ok 200 Send/recvd #1 should be same
,ok 201 Send/recvd #2 should be equal length
,ok 202 Send/recvd #2 should be same
,ok 203 Should be exactly 2 client sockets
,# teardown
,2017-07-17 11:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client co,nnection to node - 0 - 0 - closed'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2017-07-17 11:40:33 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP cli,ent connection <-> Mux - 0 - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-17 11:40:33 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'listening 52386'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 204 socket shouldn't close until after stream
,ok 205 incoming remains open
,# teardown
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing incoming connection cleans outgoing socket
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'listening 52390'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 206 we should not have gotten an error
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 207 socket shouldn't close until after incoming
,ok 208 incoming is cleaned up
,# teardown
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - closing outgoing socket cleans associated mux stream
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'listening 52394'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:34 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 209 stream was closed
,ok 210 incoming should survive
,ok 211 mux should have no streams
,# teardown
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:34 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'Native Server - close'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <,-> Mux - 0 - close'
2017-07-17 11:40:34 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,# native server - closing the whole server cleans everything up
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'listening 52398'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 212 we should not have gotten an error
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 213 Buffers are identical
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 214 native server is nulled out
,ok 215 native server should be closed
,ok 216 incoming has been removed
,ok 217 Incoming should be done
,ok 218 The mux object should be closed
,ok 219 The mux stream should be closed
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Creating Native Server'
2017-07-17 11:40:35 - DEBUG createNativeListener: 'listening 52402'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'Native Server - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 220 native server is nulled out
ok 221 native server should be closed
,ok 222 incoming has been removed
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-07-17 11:40:35 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-17 11:40:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'listening 52454'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 223 we should not have gotten an error
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 224 Buffers are identical
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 225 server should be fine
,ok 226 server should be open
,ok 227 incoming has been removed
,ok 228 The mux object should be closed
,ok 229 The mux stream should be closed
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# native server - timing out the incoming connection cleans everything up
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'listening 52458'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 230 we should not have gotten an error
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 231 Buffers are identical
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 232 server should be fine
ok 233 server should be open
ok 234 incoming has been removed
ok 235 The mux object should be closed
ok 236 The mux stream should be closed
,# teardown
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:36 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# can create servers manager
,ok 237 serversManager must not be null
ok 238 serversManager must be an object
,# teardown
,# setup
,# calling stop without start causes error
,ok 239 We need to call start first
,# teardown
,# setup
,# can start/stop servers manager
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'listening 52461'
,ok 240 port must be in range
,# teardown
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# starting twice resolves with listening port
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'listening 52462'
,ok 241 second start should return same port
,# teardown
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminateIncomingConnection will terminate a connection
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Creating Native Server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'listening 52464'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 242 we should be connected
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 243 now we are disconnected
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# teardown
,2017-07-17 11:40:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:40:37 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
,2017-07-17 11:40:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
,ok 244 Passed bogus id
,2017-07-17 11:40:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
,ok 245 Passed good id but bogus port
,2017-07-17 11:40:38 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 246 Passed right context
,ok 247 Right server
,ok 248 No error should be set
,ok 249 Retry should be false
,ok 250 We called close server
,# teardown
,# setup
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single local http request
,listening on 52466
,ok 251 should be equal
,# teardown
,2017-07-17 11:40:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Single coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:A01F0780-5874-4132-B66C-844CF07ED48B
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-17 11:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 252 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FDA92EF8-70AE-4D80-AB07-C80D2F8FD317
,[ThaliCore] Browser.startListening
,2017-07-17 11:40:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:40:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:40:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 253 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
,2017-07-17 11:40:39 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"3C2C6DFD-3481-46B7-BF2E-3B8B8326D366","generation":0}'
,2017-07-17 11:40:39 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3C2C6DFD-3481-46B7-BF2E-3B8B8326D366 (syncValue: AfjEjDcxBCjpXPydl6oyNbVstfRHGFL6)'
,2017-07-17 11:40:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}'
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}'
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:40 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3C,2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:3C,2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3,C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:3C2C6DFD-3481-46B7-BF2E-3B8B8326D366:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "3C2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "3C,2C6DFD-3481-46B7-BF2E-3B8B8326D366", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"AfjEjDcxBCjpXPydl6oyNbVstfRHGFL6","error":"Peer is unavailable",,"portNumber":null}'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'AfjEjDcxBCjpXPydl6oyNbVstfRHGFL6', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"3C2C6DFD-3481-46B7-BF2E-3B8B8326D366","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailability,ChangedEvent due to not being in started state'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"3C2C6DFD-3481-46B7-BF2E-3B8B8326D366","peerAvailable":true,"portNumber":null,"recreate,d,":true}'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-17 11:40:43 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5 (syncValue: kVZuTpQQiRHxXioQpuFJJAY,OCZMYwyEQ)'
2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0) creating a ne,w relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF,8C363B5:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:40:43 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
[ThaliCore] Advertiser: session connected Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
[ThaliCore] Advertiser: session connected Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52478
,2017-07-17 11:40:46 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"kVZuTpQQiRHxXioQpuFJJAYOCZMYwyEQ","error":null,"portNumber":52478}'
,2017-07-17 11:40:46 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'kVZuTpQQiRHxXioQpuFJJAYOCZMYwyEQ', error: 'null', listeningPort: '52478''
,ok 254 should be equal
,2017-07-17 11:40:46 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 138D52C4-835A-43F4-9A26-BD832DE1F30C (syncValue: qJpeNq4URWJqn4v7qgSTTYstgfBKyyO0)'
,2017-07-17 11:40:46 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52482
,2017-07-17 11:40:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qJpeNq4URWJqn4v7qgSTTYstgfBKyyO0","error":null,"portNumber":52482}'
,2017-07-17 11:40:48 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qJpeNq4URWJqn4v7qgSTTYstgfBKyyO0', error: 'null', listeningPort: '52482''
,ok 255 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52478
[ThaliCore] Session.disconnect() p,eer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
[ThaliCore] Sessio,n.deinit peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] BrowserManager.disconnect peer:138D52C4-835A-43F4-9A26-BD832DE1F30C
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52482
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.disconnect() peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
,[ThaliCore] Session.deinit peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:40:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple local http requests
,listening on 52484
,ok 256 should be equal
,ok 257 should be equal
,ok 258 should be equal
,# teardown
,2017-07-17 11:40:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Multiple coordinated request ios native
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:A01F0780-5874-4132-B66C-844CF07ED48B
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 259 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-17 11:40:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
,2017-07-17 11:40:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 260 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:A01F0780-5874-4132-B66C-844CF07ED48B:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
2017-07-17 11:40:53 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}'
2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5, (syncValue: s7SQVd8FfGOAmTLkJAEXmp3cYlnP60GC)'
2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C,363B5", generation: 1) creating a new relay
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}'
,2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,2017-07-17 11:40:53 - DEBUG thaliMobileNativeTestUtils: 'Already running test!'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
[ThaliCore] Advertiser: session connected Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
[ThaliCore] Advertiser: session connected Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation: 1)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
,[ThaliCore] Session.session(_:peer:didChange:) peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E state: connecting -> connected
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988
[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52491
,2017-07-17 11:40:56 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"s7SQVd8FfGOAmTLkJAEXmp3cYlnP60GC","error":null,"portNumber":52491}'
,2017-07-17 11:40:56 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 's7SQVd8FfGOAmTLkJAEXmp3cYlnP60GC', error: 'null', listeningPort: '52491''
,ok 261 should be equal
,ok 262 should be equal
,ok 263 should be equal
,2017-07-17 11:40:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 138D52C4-835A-43F4-9A26-BD832DE1F30C (syncValue: piOdQ6fDfZBdDdPrKo9Z0yXrS1DgJKmh)'
,2017-07-17 11:40:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52496
2017-07-17 11:40:59 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"piOdQ6fDfZBdDdPrKo9Z0yXrS1DgJKmh","error":null,"portNumber":52496}'
,2017-07-17 11:40:59 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'piOdQ6fDfZBdDdPrKo9Z0yXrS1DgJKmh', error: 'null', listeningPort: '52496''
,ok 264 should be equal
,ok 265 should be equal
,ok 266 should be equal
,# teardown
,[ThaliCore] BrowserManager.disconnect peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5
[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52491
[ThaliCore] Session.disconnect() peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[Thali,Core] TCPListener.deinit
[ThaliCore] Session.session(_:peer:didChange:) peer:1D80F1B1-0202-45D3-A18B-E0E00346B988 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "A01F0780-5874-4132-B66C-844CF07ED48B", generation:, 1)
[ThaliCore] AdvertiserRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:539EB86C-8D4D-4722-BD49-12F54D,B0DA3E
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1 state: connected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connected
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() po,rt:52496
[ThaliCore] Session.disconnect() peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
,[ThaliCore] Browser: session notConnected fire notification for Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] TCPListener.deinit
,[ThaliCore] Session.deinit peer:539EB86C-8D4D-4722-BD49-12F54DB0DA3E
[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserRelay.deinit
[ThaliCore] BrowserManager.disconnect peer:13,8D52C4-835A-43F4-9A26-BD832DE1F30C
2017-07-17 11:41:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"piOdQ6fDfZBdDdPrKo9Z0yXrS1DgJKmh","error":"Session disconnected","portNumber":null}'
2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availabili,ty changed event with {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not bei,ng in started state'
2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-17 11:41:,00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# setup
,# #startListeningForAdvertisements should fail if start not called
,[ThaliCore] Session.deinit peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.deinit
,ok 267 specific error should be returned
,# teardown
,ok 268 must be stopped
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 269 specific error should be returned
,# teardown
,ok 270 must be stopped
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopListeningForAdvertisements many times
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'listening 52500'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 271 no errors
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 272 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:A01F0780-5874-4132-B66C-844CF07ED48B
[ThaliCore] Advertiser.stopAdvertising() peerID:A01F0780-5874-4132-B66C-844CF07ED48B
2017-07-17 11:41:01 - DEBUG thaliMo,bileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stop,ListeningForAdvertisements()
2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,2017-07-17 11:41:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 273 must be stopped
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startListeningForAdvertisements many times
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'listening 52501'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:89F86698-8015-42C5-A648-63689727BFCB
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 274 no errors
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,2017-07-17 11:41:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 275 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
2017-07-17 11:41:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 276 must be stopped
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'listening 52502'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D9CC5789-5BB4-4483-B97A-9FB01EF9C0A5", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D9CC5789-5BB4-4483-B97A-9FB01EF9C0A5
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 277 no errors
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D9CC5789-5BB4-4483-B97A-9FB01EF9C0A5", generation: 1)
,[ThaliCore] Advertiser.startAdvertising with peerID:D9CC5789-5BB4-4483-B97A-9FB01EF9C0A5
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 278 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising() peerID:D9CC5789-5BB4-4483-B97A-9FB01EF9C0A5
,[ThaliCore] Advertiser.stopAdvertising() peerID:D9CC5789-5BB4-4483-B97A-9FB01EF9C0A5
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:02 - ,INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discovery,Active":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 279 must be stopped
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# should be able to call #stopAdvertisingAndListening many times
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'listening 52505'
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 280 no errors
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 281 still no errors
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 282 must be stopped
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can get the network status before starting
,ok 283 network status should have certain non-empty properties
,# teardown
,ok 284 must be stopped
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-17 11:41:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# error returned with bad router
,2017-07-17 11:41:03 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 285 specific error expected
,# teardown
,ok 286 must be stopped
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are started when we call start
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'listening 52506'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:710ED2C2-EEDB-498A-B2A8-D47E33112F78
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "08B2CD6A-D57D-49E8-8B1B-44EF29399C05", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:08B2CD6A-D57D-49E8-8B1B-44EF29399C05
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 287 all connection succeed
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:08B2CD6A-D57D-49E8-8B1B-44EF29399C05
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 288 must be stopped
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# TCP Servers Manager should be null when we call start on iOS
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'listening 52509'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3EC6E15E-250D-424F-A624-06776824E3C5
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "6FC086CD-891E-4700-9245-0A68EFAC47BE", genera,tion: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:6FC086CD-891E-4700-9245-0A68EFAC47BE
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
,ok 289 TCP Servers Manager doesn't exists
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Rec,eived peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}]'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}]'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}]'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}]'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:04 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:6FC086CD-891E-4700-9245-0A68EFAC47BE
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"ad,vertisingActive":false}'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-07-17 11:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 290 must be stopped
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:04 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# all services are stopped when we call stop
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'listening 52511'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:2D84032B-F909-4EC8-ADB2-CFA47CE9A95E
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E665D5AB-3D6A-4A4B-AAD6-D2E5CC0D05F0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:E665D5AB-3D6A-4A4B-AAD6-D2E5CC0D05F0
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:E665D5AB-3D6A-4A4B-AAD6-D2E5CC0D05F0
,2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-17 11:41:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17, 11:41:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 291 is stopped after calling stop
,ok 292 connection should fail after stopping
,# teardown
,ok 293 must be stopped
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is properly hooked up
,2017-07-17 11:41:05 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateConnection is properly hooked up''
,# teardown
,ok 294 must be stopped
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateConnection is return error if we get called on iOS
,ok 295 error description matches
,# teardown
,ok 296 must be stopped
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is properly hooked up
,2017-07-17 11:41:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure terminateListener is properly hooked up''
,# teardown
,ok 297 must be stopped
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure terminateListener is return error if we get called on iOS
,ok 298 error description matches
,# teardown
,ok 299 must be stopped
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure we actually call kill connections properly
,ok 300 IMPLEMENT ME!!!!!!
,# teardown
,ok 301 must be stopped
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:06 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
,2017-07-17 11:41:06 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received''
,# teardown
,ok 302 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
,2017-07-17 11:41:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager''
,# teardown
,ok 303 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire failedNativeConnection event when we get failedConnection from multiConnectConnection
,2017-07-17 11:41:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire failedNativeConnection event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 304 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection
,2017-07-17 11:41:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection''
,# teardown
,ok 305 must be stopped
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved
,ok 306 NOT IMPLEMENTED # SKIP
,# teardown
,ok 307 must be stopped
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# make sure bad PSK connections fail
,2017-07-17 11:41:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'make sure bad PSK connections fail''
,# teardown
,ok 308 must be stopped
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# peer changes handled from a queue
,2017-07-17 11:41:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'peer changes handled from a queue''
,# teardown
,ok 309 must be stopped
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# relaying discoveryAdvertisingStateUpdateNonTCP
,2017-07-17 11:41:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'relaying discoveryAdvertisingStateUpdateNonTCP''
,# teardown
,ok 310 must be stopped
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
,2017-07-17 11:41:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received''
,# teardown
,ok 311 must be stopped
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:09 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# we successfully receive and replay discoveryAdvertisingStateUpdate
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'listening 52514'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:10BEC519-96FB-4EA1-919E-B48849ACF0E1
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 312 discoveryActive matches
ok 313 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 314 discoveryActive matches
,ok 315 advertisingActive matches
,2017-07-17 11:41:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'listening 52515'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4313BE83-9057-43A9-A33F-849EE37A8BEC", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4313BE83-9057-43A9-A33F-849EE37A8BEC
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 316 discoveryActive matches
ok 317 advertisingActive matches
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:4313BE83-9057-43A9-A33F-849EE37A8BEC
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 318 discoveryActive matches
ok 319 advertisingActive matches
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-07-17 11:41:09 - DEBUG thaliMobileNativeWrapper: 'listening 52517'
,# teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out disco,veryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":fal,se}'
2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 320 must be stopped
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'listening 52518'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7DE7ADE2-8580-45D1-8E54-E134FB678FB9
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:C1119AE2-6CED-48C1-9D20-CA6950622AA0
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 1)
2017-07-17 11:41:10 - DEBUG t,haliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:41:10 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:41:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F,5D-9EF5-721EF8C363B5","generation":1}]'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"p,eerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":1}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}]'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","generation":0}'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}]'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}]'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":1,"portNumber":null}'
,ok 321 portNumber equal null
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"CF1FC3C9-6D72-4F5D-9EF5-721EF8C363B5","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:10 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":1,"portNumber":null}'
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:143BC745-1F91-4BA2-A049-76A23351B43F:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}]'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C1119AE2-6CED-48C1-9D20-CA6950622AA0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C1119AE2-6CED-48C1-9D20-CA6950622AA0", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6B833D50-0F9F-437B-A9E0-D2582037231A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6B833D50-0F9F-437B-A9E0-D2582037231A", generation: 0)
2017-07-17 11:41:11 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}]'
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:11 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:C1119AE2-6CED-48C1-9D20-CA6950622AA0
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"ad,vertisingActive":false}'
2017-07-17 11:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{,"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stop,Listening()
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in s,topped state).'
,2017-07-17 11:41:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 322 must be stopped
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-17 11:41:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# can do HTTP requests between peers
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'listening 52520'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:F563BF1A-3AB9-432A-AAC9-4FCD08AFC6E9
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:9424ABB4-619A-4022-A320-5F9F8BA181B7
,2017-07-17 11:41:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:41:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-17 11:41:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] Browser.browser(_,:foundPeer:withDiscoveryInfo:) found peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:,) found peer:143BC745-1F91-4BA2-A049-76A23351B43F:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:6B833D50-0F9F-437B-A9E0-D2582037231A:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "6B833D50-0F9F-437B-A9E0-D2582037231A", generation: 0)
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}]'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":0}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}]'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}]'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}]'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 138D52C4-835A-43F4-9A26-BD832DE1F30C (syncValue: vcnGGWdionnWyZhsGcGDbwXLnRI0OIGA)'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":1,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:143BC745-1F91-4BA2-A049-76A23351B43F:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "143BC745-1F91-4BA2-A049-76A23351B43F", generation: 0)
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}]'
2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserManager.foundPeerHandle,r peer:Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"143BC745-1F91-4BA2-A049-76A23351B43F","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
[ThaliCore] Browser,.browser(_:foundPeer:withDiscoveryInfo:) found peer:46D0B3B1-9593-4088-AF16-D54D985A55CD:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "46D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9424ABB4-619A-4022-A320-5F9F8BA181B7:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}]'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","generation":0}]'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","generation":0}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:13 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1 state: notConnected -> notConnected
,[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
,[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", ,generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,8D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,38D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,8D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "1,38D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:6B833D50-0F9F-437B-A9E0-D2582037231A:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "6B833D50-0F9F-437B-A9E0-D2582037231A", generation: 0)
2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}]'
2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","generation":0}'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-17 11:41:17 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"6B833D50-0F9F-437B-A9E0-D2582037231A","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:13,8D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:138D52C4,-835A-43F4-9A26-BD832DE1F30C error: max retries exceeded
2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vcnGGWdionnWyZhsGcGDbwXLnRI0OIGA","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'vcnGGWdionnWyZhsGcGDbwXLnRI0OIGA', error: 'Connection could not be established', listeningPort: '%s''
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":1,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":1,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:17 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","connectionType":"MPCF","peerAvailable":true,"generation":1,"newAddressPort":false}'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":true,"generation":1,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DDA978C1-76A0-4186-8090-EFD75BD499F8 (syncValue: qCf3yEQp43fQ2jeE4OrOaUaNE2G51a2t)'
,2017-07-17 11:41:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0 state: notConnected -> connecting
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CFA99B50-8672-43BB-8DA1-7303D9DB0A47
[ThaliCore] Advertiser: session connected Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CFA99B50-8672-43BB-8DA1-7303D9DB0A47 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:138D52C4-835A-43F4-9A26-BD832DE1F30C:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 0)
[ThaliCore] Browser.browser(_:lostPeer:) lost peer,:138D52C4-835A-43F4-9A26-BD832DE1F30C:1
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "138D52C4-835A-43F4-9A26-BD832DE1F30C", generation: 1)
,2017-07-17 11:41:19 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}]'
2017-07-17 11:41:19 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","generation":1}'
,2017-07-17 11:41:19 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-17 11:41:19 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"138D52C4-835A-43F4-9A26-BD832DE1F30C","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA
[ThaliCore] Advertiser: session connected Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] AdvertiserRelay.init(with:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52533
2017-07-17 11:41:20 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qCf3yEQp43fQ2jeE4OrOaUaNE2G51a2t","error":null,"portN,umber":52533}'
,2017-07-17 11:41:20 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'qCf3yEQp43fQ2jeE4OrOaUaNE2G51a2t', error: 'null', listeningPort: '52533''
,2017-07-17 11:41:20 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:18 [8, 12, 14, 18]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-17 11:41:21 - DEBUG testUtils: 'Got response data'
,2017-07-17 11:41:21 - DEBUG testUtils: 'Got end'
,ok 323 response body should match testData
,ok 324 must be started
,# teardown
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CFA99B50-8672-43BB-8DA1-7303D9DB0A47
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA99B50-8672-43BB-8DA1-7303D9DB0A47 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CFA99B50-8672-43BB-8DA1-7303D9DB0A47
[ThaliCore] Session.startOutputStream(with:) peer:CFA99B50-8672-43BB-8DA1-7303D9DB0A47
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:19 [8, 12, 14, 18, 19]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA
,[ThaliCore] Session.session(_:peer:didChange:) peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA
[ThaliCore] Session.startOutputStream(with:) peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:20 [8, 12, 14, 18, 19, 20]
,[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising() peerID:9424ABB4-619A-4022-A320-5F9F8BA181B7
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:20
[ThaliCore] VirtualSocket.closeStreams() vsID:20
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
[ThaliCore] VirtualSocket exited RunLoop vsID:20
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] VirtualSocket.deinit vsID:20 [8, 12, 14, 18, 19]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
,[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-17 11:41:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-17 11:41:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-07-17 11:41:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPC,lient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler removed virtual socket vsID:19
[ThaliCore] VirtualSocket.closeS,treams() vsID:19
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:19
,[ThaliCore] VirtualSocket.deinit vsID:19 [8, 12, 14, 18]
,ok 325 must be stopped
,[ThaliCore] BrowserManager.disconnect peer:DDA978C1-76A0-4186-8090-EFD75BD499F8
,[ThaliCore] BrowserRelay.closeRelay() state:connected
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:52533
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] TCPListener.deinit
,[ThaliCore] VirtualSocket.closeStreams() vsID:18
,[ThaliCore] VirtualSocket exited RunLoop vsID:18
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler state:disconnecting
,[ThaliCore] VirtualSocket.deinit vsID:18 [8, 12, 14]
,[ThaliCore] Session.disconnect() peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] Session.deinit peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] BrowserRelay.deinit
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,[ThaliCore] Session.session(_:peer:didChange:) peer:CFA99B50-8672-43BB-8DA1-7303D9DB0A47 state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA
,[ThaliCore] Session.session(_:peer:didChange:) peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "9424ABB4-619A-4022-A320-5F9F8BA181B7", generation: 0)
[ThaliCore] Advertise,rRelay.deinit
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-17 11:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-17 11:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,[ThaliCore] Session.deinit peer:FF7B58EF-2C14-4BDD-8729-7E0F9727B5BA
,# can still do HTTP requests between peers with coordinator
,2017-07-17 11:41:24 - DEBUG thaliMobileNativeWrapper: 'listening 52537'
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EE485A3A-73F5-4E3B-8875-AACA32AE9DAA
,[ThaliCore] Browser.startListening
,2017-07-17 11:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-17 11:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-17 11:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "F3572614-3152-45C7-97AC-98014F29C3FB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:F3572614-3152-45C7-97AC-98014F29C3FB
2017-07-17 1,1:41:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-17 11:41:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-17 11:41:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
2017-07-17 11:41:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}]'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}'
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for DDA978C1-76A0-4186-8090-EFD75BD499F,8 (syncValue: mla1vGGpdw99yQ9jOKM83XWeFqCnHftW)'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75B,D499F8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected,:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:46D0B3B1-9593-4088-AF16-D54D985A55CD:0
[ThaliCore] TCPLis,tener.init(with:socketDisconnected:stoppedListening:)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "46D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0)
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","generation":0}]'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeW,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","generation":0}'
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":true,"generation":0,"portNumber":null}'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeT,estUtils: 'We got a peer {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
2017-07-17 11:41:25 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","generation":0}]'
2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","generation":0}'
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:25 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"304D8B74-5781-4F43-ACB7-9345FE1C4478","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,A978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F3572614-3152-45C7-97AC-98014F29C3FB:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F3572614-3152-45C7-97AC-98014F29C3FB", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:58223822-23C2-4AFC-A05A-9BEDE692E47A:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "58223822-23C2-4AFC-A05A-9BEDE692E47A", generation: 0)
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peer,Identifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","generation":0}]'
2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","generation":0}'
,2017-07-17 11:41:26 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","peerAvailable":true,"generation":0,"portNumber":null}'
,2017-07-17 11:41:26 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
,2017-07-17 11:41:26 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"58223822-23C2-4AFC-A05A-9BEDE692E47A","peerAvailable":true,"generation":0,"portNumber":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,A978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] Browser: session notConnected retry count #1 for Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,A978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] Browser: session notConnected retry count #2 for Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "D,DA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] Session.init(session:iden,tifier:connected:notConnected:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.deinit peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CE42B30F-CC2B-4155-B099-9AE7DC113566
[ThaliCore] Advertiser: session connected Peer(uuid: "F3572614-3152-45C7-97AC-98014F29C3FB", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CE42B30F-CC2B-4155-B099-9AE7DC113566 state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0 state: notConnected -> notConnected
[ThaliCore] BrowserRelay.closeRelay() state:connecting
[ThaliCore] TCPListener.deinit
[ThaliCore] Session.disconnect() peer:DD,A978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] Browser: session notConnected retry count #3 for Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) peer:DDA978C1,-76A0-4186-8090-EFD75BD499F8 error: max retries exceeded
2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"mla1vGGpdw99yQ9jOKM83XWeFqCnHftW","error":"Connection could not be established","portNumber":null}'
2017-0,7-17 11:41:29 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'mla1vGGpdw99yQ9jOKM83XWeFqCnHftW', error: 'Connection could not be established', listeningPort: '%s''
2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'Received, ,peer availability changed event with {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2017-07-17 11:41:29 - DEBUG thali,Mobile: 'Emitting peerAvailabilityChanged from handleRecreatedPeer {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
2017-07-17 11:41:29 - DEBUG thaliMobileNati,veWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
2017-07-17 11:41:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChang,ed from handleRecreatedPeer {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","connectionType":"MPCF","peerAvailable":true,"generation":0,"newAddressPort":false}'
2017-07-17 11:41:29 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentif,ier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":true,"generation":0,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 46D0B3B1-9593-4088-AF16-D54D985A55CD (syncValue: d3stZXjDFJVUFvfQFuj83CcDeYMUkt7v)'
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "46D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:46D0B3B1-9593-4088-AF16-D54D985A55CD:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedLis,tening:)
,[ThaliCore] Session.deinit peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
,[ThaliCore] BrowserRelay.deinit
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:46D0B3B1-9593-4088-AF16-D54D985A55CD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "46D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0)
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","generation":0}]'
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","generation":0}'
,2017-07-17 11:41:29 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":false,"generation":null,"portNumber":null}'
,2017-07-17 11:41:29 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from handlePeer {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:46D0B3B1-9593-4088-AF16-D54D985A55CD:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected retry count #0 for Peer(uuid: "46D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "46D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0) creating a new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "46,D0B3B1-9593-4088-AF16-D54D985A55CD", generation: 0)
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) error:peerIsUnavailable
2017-07-17 11:41:30 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"d3stZXjDFJVUFvfQFuj83CcDeYMUkt7v","error":"Peer is unavailable",,"portNumber":null}'
2017-07-17 11:41:30 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'd3stZXjDFJVUFvfQFuj83CcDeYMUkt7v', error: 'Peer is unavailable', listeningPort: '%s''
2017-07-17 11:41:30 - DEBUG thaliMobileNativeWrapper,: 'Received peer availability changed event with {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-17 11:41:30 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed ,event with {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:30 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-17 11:41:30 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerIdentifier":"46D0B3B1-9593-4088-AF16-D54D985A55CD","peerAvailable":true,"portNumber":null,"recreated":true}'
,[ThaliCore] BrowserManager.disconnect peer:46D0B3B1-9593-4088-AF16-D54D985A55CD
,2017-07-17 11:41:30 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Peer is unavailable''
,2017-07-17 11:41:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 304D8B74-5781-4F43-ACB7-9345FE1C4478 (syncValue: ORT82UtvmlnR8QC0VLXWILfjW8UJ2MWh)'
,2017-07-17 11:41:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:retryCount:completion:) Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0) creating a new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
,[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CE42B30F-CC2B-4155-B099-9AE7DC113566
,[ThaliCore] Session.session(_:peer:didChange:) peer:CE42B30F-CC2B-4155-B099-9AE7DC113566 state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CE42B30F-CC2B-4155-B099-9AE7DC113566
[ThaliCore] Session.startOutputStream(with:) peer:CE42B30F-CC2B-4155-B099-9AE7DC113566
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2,1 [8, 12, 14, 21]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
,2017-07-17 11:41:33 - DEBUG CoordinatedClient: 'device disconnected from the test server'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:DDA978C1-76A0-4186-8090-EFD75BD499F8:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "DDA978C1-76A0-4186-8090-EFD75BD499F8", generation: 0)
2017-07-17 11:41:33 - DEBUG thaliMobileNativeWrapp,er: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}]'
2017-07-17 11:41:33 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event, with {"peerAvailable":false,"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","generation":0}'
,2017-07-17 11:41:33 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","peerAvailable":false,"generation":null,"portNumber":null}'
2017-07-17 11:41:33 - DEBUG thaliMobile: 'Emitting, peerAvailabilityChanged from handlePeer {"peerIdentifier":"DDA978C1-76A0-4186-8090-EFD75BD499F8","connectionType":"MPCF","peerAvailable":false,"generation":null,"newAddressPort":null}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0 state: connecting -> connected
,[ThaliCore] Browser: session connected to Peer(uuid: "304D8B74-5781-4F43-ACB7-9345FE1C4478", generation: 0)
,[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:52556
2017-07-17 11:41:33 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ORT82UtvmlnR8QC0VLXWILfjW8UJ2MWh","error":null,"portN,umber":52556}'
,2017-07-17 11:41:33 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'ORT82UtvmlnR8QC0VLXWILfjW8UJ2MWh', error: 'null', listeningPort: '52556''
,2017-07-17 11:41:33 - WARN thaliMobileNativeTestUtils: 'Retry count for getSamePeerWithRetry is 1'
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:304D8B74-5781-4F43-ACB7-9345FE1C4478:0
,[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:22 [8, 12, 14, 21, 22]
,[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,2017-07-17 11:41:34 - DEBUG testUtils: 'Got response data'
,2017-07-17 11:41:34 - DEBUG testUtils: 'Got end'
,ok 326 response body should match testData
,ok 327 must be started
,# teardown
,2017-07-17 11:41:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:41:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:41:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:41:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:41:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-07-17 11:42:34 - INFO, CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server ,that is not listening yet witheatNotRunning set to true'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOG,GER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoi,n,ts plugin delay interval'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-07-17 11:42:34 - INFO Coordin,atedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue, and run in order'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-07-17 11:,42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
2017-07-17 11:42:34 - INF,O CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - multiConnect properly fails on legal but non-existent peerID'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with invalid syncValue'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call disconnect with invalid peer id'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - disconnect doesn't fail on plausible but bogus peer ID'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Get same port when trying to connect multiple times on iOS'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - initial peer discovery'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 1'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - update peer discovery 2'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - check latest peer discovery'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Set up for no peer discovery test'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - no peer discovery'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling createNativeListener directly rejects'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits incomingConnectionState'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - emits routerPortConnectionFailed'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server connections all up'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming stream cleans outgoing socket'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing incoming connection cleans outgoing socket'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing outgoing socket cleans associated mux stream'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - closing the whole server cleans everything up'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - we can get a ton of connections and data through and still clean up the server completely'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - simulate mux failure, make sure everything is cleaned up'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - native server - timing out the incoming connection cleans everything up'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can create servers manager'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - calling stop without start causes error'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can start/stop servers manager'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - starting twice resolves with listening port'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminateIncomingConnection will terminate a connection'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - terminate an Outgoing connection'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single local http request'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Single coordinated request ios native'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple local http requests'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Multiple coordinated request ios native'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startListeningForAdvertisements should fail if start not called'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - #startUpdateAdvertisingAndListening should fail if start not called'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopListeningForAdvertisements many times'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startListeningForAdvertisements many times'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #startUpdateAdvertisingAndListening many times'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - should be able to call #stopAdvertisingAndListening many times'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can get the network status before starting'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - error returned with bad router'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are started when we call start'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - TCP Servers Manager should be null when we call start on iOS'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - all services are stopped when we call stop'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateConnection is properly hooked up'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateConnection is return error if we get called on iOS'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure terminateListener is properly hooked up'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure terminateListener is return error if we get called on iOS'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - make sure we actually call kill connections properly'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire failedNativeConnection event when we get failedConnection from multiConnectConnection'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - We fire nonTCPPeerAvailabilityChangedEvent event when we get failedConnection from multiConnectConnection'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We fire nonTCPPeerAvailabilityChangedEvent event when we get fail from _multiConnectResolved'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - make sure bad PSK connections fail'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - peer changes handled from a queue'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - relaying discoveryAdvertisingStateUpdateNonTCP'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - we successfully receive and replay discoveryAdvertisingStateUpdate'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - nonTCPPeerAvailabilityChangedEvent should return nullfor a portNumber on iOS'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can do HTTP requests between peers'
,2017-07-17 11:42:34 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - can still do HTTP requests between peers with coordinator, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/1FC08F20-F31,E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/blu,ebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-07-17 11:42:34 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-07-17 11:42:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:42:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:42:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:43:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:43:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:44:54 - ERROR CoordinatedClient: 'unexpected error: 'Error: retry count exceed', stack: 'emit@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:350:16
$9@timers.js:120:1
''
,2017-07-17 11:44:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:44:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:45:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:45:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:46:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:46:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:47:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:47:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:48:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:48:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:49:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:49:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:50:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:50:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:51:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:51:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:52:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:52:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:53:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:53:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:54:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:54:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:55:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:55:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:56:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:56:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-17 11:57:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D7,7-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-17 11:57:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4,D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/1FC08F20-F31E-4D77-90F5-9C6999D36194/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''

```
