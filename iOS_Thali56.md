#### Test 113351851fe156cf_iOS_Thali56 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone SE 'Thali56' (8effff55cdeae82604a08043752b940f94063299) connected through USB...
,[  0%] Looking up developer disk image
,[ 90%] Mounting developer disk image
,[ 95%] Developer disk image already mounted
,[100%] Connecting to remote debug server
-------------------------
,Skipping N69uAP 'Thali55' (d7a40d176e510e468af45ed03d4ca45fd18dbe43).
,(lldb) command source -s 0 '/tmp/6632E3C9-9FE5-4BA5-96C7-9C177F92C667/fruitstrap-lldb-prep-cmds-8effff55cdeae82604a08043752b940f94063299'
,Executing commands in '/tmp/6632E3C9-9FE5-4BA5-96C7-9C177F92C667/fruitstrap-lldb-prep-cmds-8effff55cdeae82604a08043752b940f94063299'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.3.2 (14F89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851fe156cf/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:58468"
,(lldb)     command script import "/tmp/6632E3C9-9FE5-4BA5-96C7-9C177F92C667/fruitstrap_8effff55cdeae82604a08043752b940f94063299.py"
,(lldb)     command script add -f fruitstrap_8effff55cdeae82604a08043752b940f94063299.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_8effff55cdeae82604a08043752b940f94063299.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_8effff55cdeae82604a08043752b940f94063299.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_8effff55cdeae82604a08043752b940f94063299.safequit_command safequit
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
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:15:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "BE4663D4-B16A-4989-A1,1D-EBEE2EF81F61", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:BE4663D4-B16A-4989-A11D-EBEE2EF81F61
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:82ED109F-D8BA-41AA-8602-E6656B935E05
[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:fo,undPeer:lostPeer:) peer:3E1C9587-CD76-4BE1-9AE0-63CE121A3688
[ThaliCore] Browser.startListening
[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "04F58672-FBF1-4122-BCBA-90E462DECC13", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:04F58672-FBF1-4122-BCBA-90E462DECC13
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:04F58672-FBF1-4122-BCBA-90E462DECC13:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "04F58672-FBF1-4122-BCBA-90E462DECC13", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-07-12 13:15:33 - DEBUG UnitTest_app: 'Running unit tests'
,*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.677741050720215
,2017-07-12 13:15:33 - DEBUG UnitTest_app: 'My device name is: 'Apple-Thali56''
,2017-07-12 13:15:33 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:04F58672-FBF1-4122-BCBA-90E462DECC13:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "04F58672-FBF1-4122-BCBA-90E462DECC13", generation: 0)
,2017-07-12 13:15:35 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-07-12 13:15:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-07-12 13:15:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-07-12 13:15:36 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-07-12 13:15:36 - INFO CoordinatedClient: 'Connecting to coordination server on http://10.192.61.2:3000/'
,2017-07-12 13:15:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:15:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:15:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:16:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:16:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4,D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:17:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:17:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:18:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D0,6-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-07-12 13:18:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-07-12 13:19:03 - DEBUG CoordinatedClient: 'reconnected to the test server'
,2017-07-12 13:19:03 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
,# setup
,# closeAll can close even when connections open
,2017-07-12 13:19:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 1 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll with promise
,2017-07-12 13:19:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-07-12 13:19:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-07-12 13:19:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
,# Call of onCheckpointReached handler on a single db change
,2017-07-12 13:19:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
,2017-07-12 13:19:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-07-12 13:19:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-07-12 13:19:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
,# setup
,# test defaultDirectory
,ok 4 should be equal
ok 5 should be equal
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
ok 33 second
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
,2017-07-12 13:19:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'skip''
,# teardown
,# setup
,# another skip
,2017-07-12 13:19:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'another skip''
,# teardown
,# setup
,# test sinon sansbox spy
,2017-07-12 13:19:19 - DEBUG testTests: 'test spy method for global sinon sansbox'
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
,ok 53 participant data matches
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
,2017-07-12 13:19:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
,2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:21 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# onPeerDiscovered calls jxcore
,2017-07-12 13:19:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopListeningForAdvertisements
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:B04C763E-CDEB-4B4D-B4EC-670D75D03BF1
[ThaliCore] Browser.startListening
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:22 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startListeningForAdvertisements twice is NOT an error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:BA83B25F-A5A0-4858-A4B9-5D5666B7EEDA
[ThaliCore] Browser.startListening
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"di,scoveryActive":true,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":",B,OTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without e,rror
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12, 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:19:22 - DEBUG thal,iMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling stopListeningForAdvertisements without calling start is NOT an error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call start/stopUpdateAdvertisingAndListening
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "D0B0617D-BA0A-4E2A-8A1E-E31FB8E3A4E2", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:D0B0617D-BA0A-4E2A-8A1E-E31FB8E3A4E2
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4ECD9C6A-3F2E-41C5-9455-054E4E26FF70", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:4ECD9C6A-3F2E-41C5-9455-054E4E26FF70
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "4ECD9C6A-3F2E-41C5-9455-054E4E26FF70", generation: 1)
[ThaliCore] Advertiser.startAdvertising with peerID:4ECD9C6A-3F2E-41C5-9455-054E4E26FF70
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:23 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:19:24 - DEBUG th,aliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdverti,singAndListening without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdver,tisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:24 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# peerAvailabilityChange is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C0AA7A60-8928-4575-939A-3DB9D261CAAC", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C0AA7A60-8928-4575-939A-3DB9D261CAAC
2017-07-12 1,3:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:19:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
[ThaliCore] BrowserManager.startListeningForAdv,ertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:277A777B-CEB5-43B1-8292-F7B555031A2B
[ThaliCore] Browser.startListening
2017-07-12 13:19:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryA,ctive":true,"advertisingActive":true}'
2017-07-12 13:19:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","sta,r,tArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C0AA7A60-8928-4575-939A-3DB9D261CAAC:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C0AA7A60-8928-4575-939A-3DB9D261CAAC", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:1D34F925-0999-4B0C-A7C1-80153F143540:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "1D34F925-0999-4B0C-A7C1-80153F143540", generation: 0)
ok 88 peers must be an array,
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
,# teardown
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:28D672EA-BDC0-451D-AE1A-310791B29438:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "28D672EA-BDC0-451D-AE1A-310791B29438", generation: 0)
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:19:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 ,13:19:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
2017-07-12 13:19:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:19:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:19:27 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:19:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can connect to a remote peer
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:E59712F0-72F6-4566-A8D4-829A16C30569
2017-07-12 1,3:19:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:1481B5EC-DC99-44B8-A43D-0D14DCC58FCD
[Thal,iCore] Browser.startListening
2017-07-12 13:19:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:19:28 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:28 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:E59712F0-72F6-4566-A8D4-829A16C30569:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:672362F3-126A-49FF-B6E6-EC96571CC220:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
2017-07-12 13:19:29 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"672362F3-126A-49FF-B6E6-EC96571CC220","generation":0}'
2017-07-12 13:19:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 672362F3-126A-49FF-B6E6-EC96571CC220, (syncValue: IwtMdpwrQaXzITXbenGeHT9baVz4jcqx)'
2017-07-12 13:19:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:672362F3-126A-,4,9FF-B6E6-EC96571CC220:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:21D61C85-BD37-4F2D-8D82-AB6BC93A2CBD
[ThaliCore] Advertiser: session connected Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:21D61C85-BD37-4F2D-8D82-AB6BC93A2CBD state: notConnected -> connecting
,[ThaliCore] Session.session(_:peer:didChange:) peer:672362F3-126A-49FF-B6E6-EC96571CC220:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D07ED69B-057D-4B8B-B6E1-38CC4EB251F4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB251F4", generation: 0)
2017-07-12 13:19:30 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D07ED69B-057D-4B8B-B6E1-38CC4EB251F4","generation":0}'
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:21D61C85-BD37-4F2D-8D82-AB6BC93A2CBD
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:672362F3-126A-49FF-B6E6-EC96571CC220:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:21D61C85-BD37-4F2D-8D82-AB6BC93A2CBD state: connecting -> connected
,[ThaliCore] Session.session(_:peer:didChange:) peer:672362F3-126A-49FF-B6E6-EC96571CC220:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[ThaliCore] BrowserRelay.openRelay(with:)
,[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56669
,2017-07-12 13:19:32 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IwtMdpwrQaXzITXbenGeHT9baVz4jcqx","error":null,"portNumber":56669}'
,2017-07-12 13:19:32 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'IwtMdpwrQaXzITXbenGeHT9baVz4jcqx', error: 'null', listeningPort: '56669''
,2017-07-12 13:19:32 - INFO testThaliMobileNative: ''
,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
,ok 99 listening port should not be 0
,# teardown
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:6801D4AA-C91A-4AAD-9A8A-F42CF1D5111B
[ThaliCore] Advertiser: session connected Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:6801D4AA-C91A-4AAD-9A8A-F42CF1D5111B state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:6801D4AA-C91A-4AAD-9A8A-F42CF1D5111B
,[ThaliCore] Session.session(_:peer:didChange:) peer:6801D4AA-C91A-4AAD-9A8A-F42CF1D5111B state: connecting -> connected
,2017-07-12 13:19:39 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeni,ngForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertising,A,ctive":false}'
,2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] BrowserManager.disconnect peer:672362F3-126A-49FF-B6E6-EC9657,1CC220
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56669
,[ThaliCore] Session.disconnect() peer:672362F3-126A-49FF-B6E6-EC96571CC220:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:672362F3-126A-49FF-B6E6-EC96571CC220:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:21D61C85-BD37-4F2D-8D82-AB6BC93A2CBD state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "E59712F0-72F6-4566-A8D4-829A16C30569", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:6801D4AA-C91A-4AAD-9A8A-F42CF1D5111B
[ThaliCore] Session.deinit peer:6801D4AA-C91A-4AAD-9A8A-F42CF1D5111B
[ThaliCore] AdvertiserRelay.deinit
,# setup
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:5FAD275C-C5BC-43C3-B770-A6845C0A2152
2017-07-12 1,3:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:A00410B6-5ED5-41E7-AB5A-EEDCF0B491F8
[Thal,iCore] Browser.startListening
,2017-07-12 13:19:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-12 13:19:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-12 13:19:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:D07ED69B-057D-4B8B-B6E1-38CC4EB251F4:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB251F4", generation: 0)
2017-07-12 13:19:40 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"D07ED69B-057D-4B8B-B6E1-38CC4EB251F4","generation":0}'
2017-07-12 13:19:40 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for D07ED69B-057D-4B8B-B6E1-38CC4EB251F4, (syncValue: 1do36tMQSGQus0UZAsYJPyMgR8RyEBP0)'
2017-07-12 13:19:40 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:672362F3-126A-49FF-B6E6-EC96571CC220:0
[ThaliCor,e] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB251F4", generation: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB2,51F4", generation: 0)
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:D07ED69B-057D-4B8B-B6E1-38CC4EB251F4:0
,[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-12 13:19:40 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"672362F3-126A-49FF-B6E6-EC96571CC220","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
2017-07-12 13:19:41 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD82B37D-D503-467F-9AA6-26A0F563A03B","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5FAD275C-C5BC-43C3-B770-A6845C0A2152:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5FAD275C-C5BC-43C3-B770-A6845C0A2152", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
2017-07-12 13:19:42 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:D07ED69B-057D-4B8B-B6E1-38CC4EB251F4:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB251F4", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:D07ED69B-057D-4B8B-B6E1-38CC4EB251F4:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB251F4", genera,tion: 0)
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"1do36tMQSGQus0UZAsYJPyMgR8RyEBP0","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '1do36tMQSGQus0UZAsYJPyMgR8RyEBP0', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"D07ED69B-057D-4B8B-B6E1-38CC4EB251F4","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:19:45 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"D07ED69B-057D-4B8B-B6E1-38CC4EB251F4","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:19:45 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:19:45 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 672362F3-126A-49FF-B6E6-EC96571CC220 (syncValue: 7QrImLK,R7nPfpeegpV7VSFQBKXUrZ5MK)'
2017-07-12 13:19:45 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:672362F3-126A-49FF-B6E6-EC96571CC22,0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:672362F3-126A-49FF-B6E6-EC96571CC220:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:672362F3-126A-49FF-B6E6-EC96571CC220:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "672362F3-126A-49FF-B6E6-EC96571CC220", genera,tion: 0)
2017-07-12 13:19:51 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"7QrImLKR7nPfpeegpV7VSFQBKXUrZ5MK","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:19:51 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '7QrImLKR7nPfpeegpV7VSFQBKXUrZ5MK', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:19:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"672362F3-126A-49FF-B6E6-EC96571CC220","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:19:51 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:19:51 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"672362F3-126A-49FF-B6E6-EC96571CC220","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:19:51 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:19:51 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:19:51 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD82B37D-D503-467F-9AA6-26A0F563A03B (syncValue: LjAMBtt,b51uMZXaSgz9tNtVzieB2lBh5)'
2017-07-12 13:19:51 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03,B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:D07ED69B-057D-4B8B-B6E1-38CC4EB251F4:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "D07ED69B-057D-4B8B-B6E1-38CC4EB251F4", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56676
2017-07-12 13:19:54 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"LjAMBttb51uMZXaSgz9tNtVzieB2lBh5",,"error":null,"portNumber":56676}'
2017-07-12 13:19:54 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'LjAMBttb51uMZXaSgz9tNtVzieB2lBh5', error: 'null', listeningPort: '56676''
,Connecting to the localhost:56676
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
,Connected to the localhost:56676
,2017-07-12 13:19:54 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-07-12 13:19:54 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:1 [1]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:1
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:1
[ThaliCore] VirtualSocket.deinit vsID:1 []
,ok 104 got the same data back
,# teardown
,2017-07-12 13:19:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:19:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:19:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTC,P: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:19:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
[ThaliCore] Brow,serManager.disconnect peer:FD82B37D-D503-467F-9AA6-26A0F563A03B
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56676
[ThaliCore] Session.disconnect() peer:FD82B37D,-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
[ThaliCore] Session.session(_:peer:didChange:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0 state: connected -> notConnected
[ThaliCore] ,Browser: session notConnected Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
,# setup
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:19:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data via parallel connections
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:C8754D0C-B89C-4AEC-9174-3F312C3160A7
2017-07-12 1,3:19:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:19:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:7CE35899-5B9C-40E8-BB55-13F9AD7E046A
[Tha,l,iCore] Browser.startListening
2017-07-12 13:19:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:19:55 - INFO thaliMobile: 'Received state ({"discoveryActive":tru,e,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:19:55 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] BrowserManager.fo,undPeerHandler peer:Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1","generation":0}'
,2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1 (syncValue: 05JwvpIT3xZJzePQbFhyOGJPq7qxj2ho)'
,2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FD82B37D-D503-467F-9AA6-26A0F563A03B","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C8754D0C-B89C-4AEC-9174-3F312C3160A7:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"188FFAC5-6F17-4776-8380-760277222EAD","generation":0}'
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C089239F-FC8D-476E-944D-1E38E0C79965:0
[ThaliC,ore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C089239F-FC8D-476E-944D-1E38E0C79965", generation: 0)
2017-07-12 13:19:56 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"C089239F-FC8D-476E-944D-1E38E0C79965","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1", genera,tion: 0)
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"05JwvpIT3xZJzePQbFhyOGJPq7qxj2ho","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: '05JwvpIT3xZJzePQbFhyOGJPq7qxj2ho', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:20:01 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"48C5A4A8-57FA-46F2-94D3-ADC762D5DCB1","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:01 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:01 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FD82B37D-D503-467F-9AA6-26A0F563A03B (syncValue: ETEeZqN,QE287vmFfEranA2pLr3NJl57D)'
2017-07-12 13:20:01 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03,B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
[ThaliCore] Advertiser: session connected Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
[ThaliCore] AdvertiserRelay.init(wi,th:on:)
[ThaliCore] TCPClient.init(didReadData:didDisconnect:)
[ThaliCore] Session.session(_:peer:didChange:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE state: connecting -> connected
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
[ThaliCore] Session.startOutputStream(with:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:2, [2]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 0
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
[ThaliCore] Session.startOutputStream(with:) peer:CF501BA5-CE1F-458D-ADDB-D216249B,1ADE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:3 [2, 3]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
[ThaliCore] Session.st,artOutputStream(with:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:4 [2, 3, 4]
[ThaliCore] TCPClient.connectToLocalhost(onPort:)
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 1
,[ThaliCore] TCPClient: didConnectToHost, active connections count: 2
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server received (1095 bytes):'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server received (15289 bytes):'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server received all data: 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'
2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:2
,[ThaliCore] VirtualSocket.closeStreams() vsID:2
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
,[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server received all data: Qb1Mw9csuSZ72Bp7OURRIi0VMwxM0Vip0uZjM6sgTTT5mZiornYthS0PWpAv0UxJXTzjQTPWdyf7kjL5ZteBIxWd6gIhbfhADwKoZWYTdqBDsWEyt5JtLZnIjsbHwuygr4QcuJAOTEGMGFNZM2pOBpqcFKXlNjQ4F0J2eq3sQNrkiUJuoMm3J0MjtuQNZr0OtvVNz9Dt7Dwc8ERzjJztUDM7OD9SKAOKNmeGwfRddL9WNBjrVLQJBL5cNMdYmu2VvvpKLSB0KK0Pu8itYm3cv94WRdFqv5lX5HBbRZMzY8bCXDTMst4upwzOZhaZMcd99xhG3F0OY2BJGyltJdgfjD2VzhfcVMS7ddXjLfKg1JJoPwgEjEmUSk6TZNXq8S6WwmdcuYow3AqDVYgNZirPxGrZgRKrZ4cCSCCmq48O1eV2mYzHIH,r6llERdEsKsca2pkBQMhO1cUM3Kzgdyqn6fDQzcNWMg9N1r60m6kKpEAauZUaGtRslLAoWnx9okCDokawmlsZgADSv7mXMeaF8mQOe8cblzxUc1JlWBervdoqsEDD4xR2KUfPTjakByd8bnmsrTXWNPIavE4uaDP8DKhDGosKkfzF1mrutEXMF7ZSTBfHHBV1oVYDEBOxsB06ownoB5T0GX4S3XuMQmAj5ILQXvqTOaICtNeZ4YeLmXutSsmKFk5,URxzRHTAx4FbUMrA3H0EDqVZvXHjW9PHq7RhwQSHDJPmstuJXRDWypSIMi2Bmev0qluRbkG3NtLDIkmchEFREqNlgvfqKKMSoPxK7Rfk1cpwjwsFmrLTTpC39POiJPhwUFFXR3jtC7BnkVUEcMsZ1ufVELBSCvrxRmDLazYltpVlMECq8Gln7Ov9wtpuljTzuKQfHYlggtsOK4ZCw0R8aOmz4wiL9srxFDm2Pb3DFgRegiO7dh29MmBMiUVj1OJ3,TvZmHC0yIPxiBoO4s2yJDD2N0Klh7bSvRx8pqnuSAsAhUxqoN39lBIo8Rfnix6g5uKrU4a5iuCUILHhgrh1iYOHekH3zMEUKAGEx4OjMNIsxaV5g3OUdLPUR7syqlRdWz9SH3QVFQMLNHZNUAkk0B0Jr9FsgpZcNkkGb4dqeUtHal9WJ8dXmaGtCMoedWHrKhwHeTO12nKrPowiglYYQWfp10X4EHAKqz2WqWxZ8bK6PvGjTfoYDQ3wxHbCFH40t,dvgXsQPImLatz1Z2puSA8AUi6Aicpcy82t35SbnaotkynjPmZqANtZOMxEamma9gmGYu73NcEUttaqPslUCMnrWO1kqXu5v1ZgKEY1uywCnBS9LoV732FfUMYlidVtDOusCp3K1LAVe29t35kJsTuzEF9wTCvkNpuF5somk0o6VFgiGtRwKvB6X8VwBzYGiGcyapw5JvytHIMRcLZmwvvFcJFyDyXs16lvJ2vGbOpte5Fsepgm7TheM9tEVh1n7l,1QM1ytjH1ULMZUzn1fjIIpxssncs7G4WGLJDTTruMILOrbhMEncsST8l0H1iFn8VWm0J8UuifxyZQxBY8VYWXl3u2tvVfoZbKlnZWOdCthtnh5nNPlikdBTTRKUW3u62LfEbARDvkiVvHmhPzHyxJGpXtQZV89UZMeVYJCXAGMoI1C3GViewNvc4bf0uvTZWejcb3ozHut1NMQViwHk43ybJOzB4GuHx5pKlJlMQOK6uAe8SnaF1c6dEBEofSHDg,e84ruyMLr9YFHiQy7QzrqurcyFGH0TemclQVVp536qXgQe3Z73BDD1pSZfNY7LHNXhNdGVdFoJmsZPH1Ykpub5sDhfiHnvnCfWDj0pcydKgeRPudrehBzRr7eOnEb8gMoqT72iS26P61cJRils6wyORC34ESS8p7NtsQBwinkQYh9mN1HiEcASwt3x2eR2ybGIWT0W8dQdXrKzysq7avUKKnB2LpGd5o4s0EJPjgNZ8MZ5RrntqyvQ1AtkyjUdVP,93tkFgVSk8q8hYseE8h2ROvpmco7fUaOrETsDJ7RZFfikjP6Ih1jLCzG5OYKJQmNoZ55RVfCkrb371A5qcpwEuyITXn8Gc8gCqYHRt7jIUfIiNw21rOksidh7TrSLUm3mLHHo9rVyAkRWdJddHA3iC3OK5u0d6VQ23uYVlMIvBseGiIxDHTNj4a4UoMXFIxx5BaPpKZy7oJx8GUqurvWbcUabTOSQSK7Lib8FE51qaXC9g64RnFbQGQhAfjwSlIt,pMbW2YIgtqAyDWnjUftpuaEWnpmWCXvhAcTYGCw4LusoQwgAlBGs4Ka8I6V0v7fUdtPdNxYJvmTuUGhSx2MBLlefgHZMRfejqzpxfLAMBdx0IXFFkDnd9LZIItHmcA7lEA836ZWoGVPM1hos5EVvReLJ7WNNjokPQqvNVEvYSwn61MoxZkUUm9rePrzldRLni9TAOKWdEhyKAYismfeIBERanq8O9FFaRyEtAEVBFVVQeC4ZcAHiLg2IqSBWMqoq,Nimg894Qaom31iIxXyThq9RjSk2EH3jllz5nZ3nyXk3B80AFppp8KWtOn4C430LItaVh6WB3AZkjiudNznqzsnR0G9PCIudTV6wUUHPVy2Caj2jTDXU6YrWde07zvhOLDl1bzvxso2oan9Ln6ZfmzLrn3CTS7K5O1y0Bx1zcdB974ss8vzJF39Cv2EcIQJYVsJugvmb2bjohNXoMWtgxD2dMogLP8yU396hBUtDchmlKYtpE0ViUyD1cDOXwRw3X,Ade7ZBxL6c5s0HrqrScd7Y2Xea5ylL6ern87TJjU6mHg275yW38Z0YBWwNNqiBY69p7WJJaN9bA7buR3JtBX5rB0XUMs098F7zZC3n7vKtek1hwMRCGvRluLrXL74gHKsFxveEAyLwc0LpinmaTa1yPS9GH2ddIkQqiMDeHoJTo98rbrWMu15fGDXattmlE9LTQ8KZc4IONA6AfRb0hspWI2uEmCSZzAZPKLybWiBUmMlCYbKqFfG7gHLrtgaGWI,hCuDezpXLwK39tYdJgLscgpHnJntUXJmJ7ZROEPSKf0LvdAifQasA43n8P3wlSyfFwmPDLjVR1MeayVk1Hz1o95HE8b3flrrBZcVPDhWpW3337PGuHpYeoVWkg8wzs8O7rXNkiMrvDiep8zq5e09etpbG05fVomYdqYB22KfrDSJyVpN5s3nk3d3iiSQvGOjnEbFqZ2jZZidPkbvV9A6uvKLjHrYTpIojhWpKHVjJOed7ZRfAPzE5r1jcp9Y1A49,Ed8CAIJWuMRhD3VqHbtvhVcK5AHaEvNnTHEA75API43JOt8XTP9FXnfIWOet4CdSBE6KDYQ9dXvC2s6Jsl81Z1fza0i93WIIkW51E6jmXmubkBoYJY4358K4u8luvlRN1ax7UCKxg94GjJpZJVvKYpkiZwDRpzsVHNvwsSUucf4jpw8f07igpCU4XmxUlRygxfpgfvASLAtauO9FJwoflPWx7Lv1fxxvsw2YIoCXXXDXTnjtrFIW0rqM3pefxXa1,QAGH3WtmmSKKv41iHsIWe7UDXqEazR45b01j2PePrWnd5qlPfM0MGcyGDNSTIesJnpgyQFoEmSOMuUpMhea0QgzvKkrSla5WHFhkzWdbAmwxmBSH2HaHzv25ElWRFQhjGemZIcTAqn9iU5EIEiVHA9qy5Lw3eYE8KPO8dszvAAgRjaISrjDbbhFXRuwWaMl7fEWfH3DbyuNTW4t6PVHSxUq9nOHHSDxQx5BMg9qsuYPbFTHi7fH5IfLsitF4irtH,DoKYmBAzfvPC1EYMuIt1HN7yl4IIJkLbRJa4SWHLM87srR2XBTKKMar6CJlTkFVvMaKhPc6hjI654OPSRgYMLwJqICEqkX6NSUp6ammx7T08POeintLlqgOcJaORGoWNb2O3fPnpvgFxdd67xHO6OxT9b5F0xLDFT294JufOeaGKYIOWatkJtaBf8pxI4gEZQRBmJ9VgK97ewFQXGikr1r8BOEd4gGZIqLtFB6JSrT5v56rAznW4tzIShiMaMLtw,QacpgoFYzjTqVa804jJ5tLDVPqhi1fVb90EL9uZWPhgYWqKsx6prukyMf2afJCBkZCajiMm62KrioWDZLAbCXCqeNFW4quNiOaurlvdLSQDYJMsQAJGODu7jqFUkZW5Qlp8AFYIh1Dix9WMbXACVoxXBPEukl5Ms94Bewp9j8V5PQe9RxpQlf2Kit2gXVj9Uvv0M7piHPHwDOIexIA3Rxov3ygQPHUk4oi6sscnfrS9N7PpqhPcIH0cDnmly9qd5,ZoI9QsiYqpkKekTKbUqas34DSr1OwQyxun06IQeYstE9Ifm0y8EnKBMor2xgbgh66GzcBwHQBwouqfhPXcOfh3nZ2hg3Akr4Nzunn7i2SsuhoDZ2dTQoolbJO0yZUQxUIRguzyWfZGf2DUFODL1OJwneG336Cl1Z0pZ5Lh0zvVnpPSoTzlX5SFWyntzWzSi5XargH4yLh8Cp8luFSmfSEWuDSUKMpxijPnbOLqpyMFwWBtr8tfvGqIwMAoZsRzei,p5LU2TcgIr42sAp2wBwAuIMu8IMRPkE2GI4O8MqGgznbmYIiTtcGlKjICbScbYBdfvw3H8XQVLxp2T8wYuPiuM1NFWL6VzBFRAvbAelSehVlQoPfHsaf3VnYTZV4kv7vrRwy1XeEqZESRg3gYbCx9SuOkfUnzZ9jYsBJGhdcnxRqzFVYS3myINbRAxa7Zd1CmYK9MBBi9zsi7BbYYbqHvAscVAiKgN68zWfGjxfufRmppEe65EWD9niWB8JGgqNn,7v2ysyMhZ9DxrhQSyNcHmRZ29kxg81WvsLlwJWZiQbgfFZeIZDgCwseztDR4OrRIrkPYH2LqyRXjHpVZE81MGXqgIBl4seteRWVJQZ2fYpAqaHMdabqLxciVQ1PhDQrVs1eHOkBWQ1YCva9vGjMz3ZejQlnDms6yNHfRAHXMmOeDeUatNvKl9WhtUlIr9mHlJ58WGhSIYuZpjt7hWmwEOafBGZh1jEx7n2LNaTvvMWHjMPeWpnPZSxi4nHjVpyqQ,6If04PHrNIMfDzpqhuVs0hnjQbYcXcp6JJBdAt25C6vjf8H82w2g00Ivc4Iu9WzjyodZPmExXY4mJ9GXJEn80bimUvIAhhBIHVlejSQQmuc1sTsjQuc9F8xoTHm2k89fWlKfLBjHfCQFvwevskai4Pzaf9gS0Vo1LUV6F32XSc0SHvrfxf0wAQMUCHviC779JdfWo2cVxAg8YOzIKft68lUYTBf8IaX3JqTaiB8OBszNDBs2Tr5EBBFyePs84BPm,CqUYR52XgybYLae5d20VzKNLKoEPeJKT1NWwei5Z9cZF0SJsQK5A6GO5ihTmpOAYpvsqZvvSI0rrZZX3LCKdY13zGq7y9lJtzIVcavaGz2rIPx3PwJUhkG7ePYXDA8d5SF57L9tJRexpBhecFLvtMs7q9JNXNH7iBEik9HXy1bui2nUdBdOT8fFdZcsORsKhcnz7My82g2kb6PYvLfJMhrJcyojLJlxMRcpNGx3Vsy8g43Ej6Sr318w17jsfU0hu,9Is0o9jrOPIui0X9DzgnFOnM70V8DW0bgX0W0I2e4m0rFC3OejHgisNY2nq1N0URTX2koO7sj9MfKhPUbBp0RZ7KABNPdPLS1j8cPrORLeZDIQnD5JAGqkJCstmvEiv901UEBTRbFcpJREm8zzTHluV5ST64g3WCOUJEJM6r51NHbCT0tk1S4No3AERydWlvXDPQytMzRHZMKYnO1pPBbKpVwL9eXi1iDcHH81k9bp4lR4f9e83YXFxIhk7qGD2f,DHltupu1RhwIZbgMNrxmOyEDgKMhr9VD2IXwpKpzD6BgKqd8XFHz4ejYfHpWRK4sNobLyS99TeNw37aecCtf7wlgkt0dE1TiD2WYhXLwXRWERfKtGBjCYAfm3T9uvLvBPVIoI1kjvdM4Q1VzX08oaLaxH8gerwBAJlt4PeswObPK2jpHsmntioztdIlZ3lxzYGdZpRdzw7BYliwW7zBOH8ksur5rPIcP9dLNfSmivqFqnv3SKz1cCBxnkSW9O3Pk,EVzrERGIy9aZUjLPbR2QUO7KBQNou45UreJULXPCf6CPysZ8hAu5ODURPlWcFxAXvC3IcHYqiruSYpR2nOPJYxeEi7PStHwcHMVUmKFo6vx6bwKck4XFC6nkT4eMMqe4DmWDTV6d07lvsVl2FMwNBCJWgCJr1laJzekDa0UnWw4gDNI6VAXE6bYBqhuY3KIVFJ4Pt7JlnOtmwf0mpPO0CoZae09GOBHzusPBLobJkQ9DnqqlL5Ss9CSuC11Ds4Dl,TjgaF5nosRxRdhAdwTRSilSfV59pZaiRAckgbCHyg9uC13o8VVRPr0zBtjsrRFEZvTzXNPCoFJ1UC9FVNwZ9eYewYRZzUC9ONsHAGsiv77Yfd9Ag0Fy48H27lP8ncaz06BB2r7EGgFMJQmyWOWFqxKqPJpFWU4443J37rmvY0mmzSaIsAAf9oIsFzUnUoWqTEJ0ZGW0v65Q4Z4ARLV479ehRJ37F3CqeqWOQAvlCRdptYnxbMGaEKYabOaNZ4D0h,ZXcqg4NSVA35fwATtSH2SfH6KBr0xpWktEV8i8h3MWhormUKDeqJkZjpNB0tAq8WAdIj7rjqWNJNes3Jl85ogfp8tcFMh4M4hUDfV5pRv7O4vE06kF4PEw6VSn5mZqMU9SSLFDGwWM1VzGkymzHeyp6Ia00CkEeyLvc0itrM52rgFAp7HiluyyuLlWvCng30X7IFVdFs8P1tPBM2DltKS6Dmr5BkiYrQRJNaADcfSYdf3SqMpWFvvqp5TNiD9Zdw,74EFozs2yCX6UkZjkrGCVY6SHxmUsjdBBwmlKwEZHm7voDwglgMYPNsKK0q52HshkMXoJiwDzSavUVH0lksQk8pHFXKKVnjjRWNZGHaIq7D33oNxn6ifcI18rdTvB7OTt7smjoA7uF8DMatDbObs1yc5gM4WBPk9owuOvEAu7NcxwkThVtBEW8Opp143AKDPvNMRY8WQshSXm16Ixl3i7394w5W805NklKijU0KSlMCKbrln5FycOBoGpszKO7gb,2ZDY26ivvPxniz3mjtiwrqAIYthEpBP51ya2flGJRGOeANJI98Qo3NnR4cXr4RZ0qRGkIMgGFeclHL1b4LPfZ56hCQizdgvoks2uPZ5pYHIVPAkf95YPeH0fuHUT5gWYZZqBAqatL24oBfUby7BfJuCErtzAZRHL7tPxa3md41z1YGqX6DexmpRdvfWpab7xi9802z8FYRdN6Ri6As5eGOMJ27B63DlJK4w29Hmpsc0Szl0yARJz9WoJ0J9KpG4G,S2cEMgdITBcePeq8mXrrCr9CX3ytZh4hpkOryVvzcNqLblcsqTUjmhdYlDLDDu86rCgSBfoKVXCS2kWVU0eCv3oIPZOaWyxboypOYJ3L2MreQplhrCS0D3MEaRO065jAYxiBQBtKVE57ZlkCRDT0toSIaznUj7o8qH7M2lIyr8gXVEG5u3y6HjK3gaareTB8WqNvUxOVZ006q4ZMGh9YkKkDL2zGX6rBe1KcfjoJ8InsmhQ7A5bnfWlBiYkxB4Jy,HumSzGyKUvWGiCuVf0XUahIkPecoIIrLkG0AY7nqqFRmAG4cMQAjTd4VMwrxPtolgK2MJ5SPDr0rP6Qxz37GpUHTxk6p444rkboXhjeWs6MakZyW4Pn6IrKU6NWnyWpBLDVXNOC7N9KSpHBh5s3J0sPc6rZAqchdufAe0mSQwJc18If0g2YxsgOK8s3e4VE0HbWu5uV4sXK7HKpJBi7jLNK9wlRWN0Xa8xze3swzVThlPj1ymHpNPGOPihzkrJgZ,9cgBOHWJGrF130FGylZttEC4guVYACyXhWTQIdi5kIUGYgPYiUt2RReyxgyNgWWUOw4zFtlCqNkIVgizPc39Rb6PrYtDxPwPJCPuHNVq9kNKYjoJ5eOiC07jUPXd9XKdKRR8zbagNa1C1uR1vVOedd0wOaOPiHAzVmeCJSIyCPlxMYJkz7lCXRz9SF5EsCDzlfXa19Bmh0Sum2QGaIkH5UsuDwHTe2vujYSgd8pFesTf9hM8IMMEx9rh4l7vGBOl,uPBr1emZh8de5cdBd3vd1Ls6YnVLPSsVUNjKnGhrnd9542feZnogvPyyIVgGhX1DXyrkAqxEuWoT9zXYek84IcqK1EKnDTEY8tC2njA4Uk74MEK2KplsBztbri9bBMZ6HOV3F7QY9BkPVNuevpU6N6JqJBmDSpT1tPhRBwGUNrSN7HdsJFstvvjrIdpDE8jKSM9gOUhFGROxbwbsGiRdtECLRcVIH8aFhPkaDox1Zfs6LC7KExoy7cF7NpuyQkie,AT90bqy4RNDQdgr0WEoIhXGy2kLNVq7UfOurmJ0FPTAaTS5GeM9P5LYRCY0H2STNnXniHxuyQE5ECldw4KBbeY18xUfXGolotThE5rNCiIrGZRpgeptylAuhcqufmcLWyPzJ124WMD0DiauSPvPXLczJMh5roidqyVcqT6IJfYG9mR2U2iSgu9ravs403uh9QxdueCC2LoyWK6ubPJYfMZ8VL7WQWsMLrtuQKIhVUqWWN8phVEhkjjZkwtbDD6xG,F18VsF5ocKADz0Dco1W6On8iidVfkgfFoEJusw2B4rwNwD3Fa39hUab1qm6a4NZjR4hMsKVcJdZn4DbsjmUuTFLRS6HLVu4zFE3vVk7iea0XAi0iA9cUtOlZMrbQRBWT3vKEPSHq4l8roMmO4PurQfHMGlpsryi7wYbwyFrQK5YWXyLsPEN4YpZkgWfdVmUU3JiDSUFf7QVXEhaKr6j7NGM82C8gbGehpVWY6Q3TAm8DTxunPBrHBrmYqttOyGWb,eyFIKD6TvQE417NSPDaWoJYITw43pp0GyS4txFN9o10mKYyEqc4md8pj9jeNUaBBDZCiOakjfkklPVrnrUryaufmDhtw4V7oPzClvdj7AaNbFIcOVtO4GVonxizZOpi5lKioWKXs9Pd2fovssJfK8A5pmpxvs9F4QLSTLuqEi8d7DwuJihhzIYpcL9WB40fr7WQXCARN9WgZnnu3FgGhAfnEfFzY1p7k2SPN1ET9cLvox1XrDEw2edj8ljzSbAd3,wyKEWjsiAqYgoUcQWTTTfW1sFdJmD3TMXsstq3sfNw6ecSQmlxaXXd6XbnUxeoa9vs87jbJhOP0sDb57TkHWjibQmWhy6ISkK1KVSKvNWMYbF7rkTzc3rY4hgE5RRsYSlQiwPSlVFC5cq1Sa0IM0lERHFVIvx7Q4RyJ9t9Nrl5VecKrW5C7FcDJzMdSvmDWsUz7Br1Oew7VYtyOub8dEksi5Ev5eM9icqsalBy10vcTNU7woqCZUQ0SH3K8KCa38,2AApRu9u166xFYcG3aN4J8nksThOZJNK3TWVg4MxNShHiYjwcuqn9JRSSdpZ98ooD0RyGRjGX912reqTnoElnCkmSvGvVmYOKzKevXnsUgR7l1cVnV9zOSqYUNFmOW1r5T05XlPxC8ktnoNqpKtxbd5UGG2fMhirAEakv9gE38nWzjxHQ5lkR63BdBzrOf2E9z112g2E3MESnZuREB8wSmYEgowDnYVpt0k5yuhFXQL9eBPp9zz9GVGfUYvAHJKY,5DH1kwxxXTNlj0fdIDoRx3Sqq9cXSMV5uAap9ZnemavOx00am8bNEYZZjsBk0MbAtlu4bVPHWtrGNRcgwfjbZtAKjrccz80ujjIIK1SG7HajBeYNU6jBdL10w6Vv5cBVAkRb17n9iDBitZQCsYXJ2nIH1ub1EohgWjofFzxmiLQ70OjnyDfRyPV8IjjWuqarssgqIty7fBvzCEYbl9aQpc8m8N1vg23Mx7wlGu38eV7MApm3yYjd86qsc11Zqo0O,w2VU3RGQFXxczYsWpO9afdxKxkkKRPdY2PKZw7Kwh6BBMnp25AgVRjnBowpAbsoMQzST62EjIrHg8PXd1vMoTYu7knRSTBX3ajxi2eqkrK6AvGrpjbQ3XsH45yWXXGqZnCkQQxy454ggJiycJjOyqQzRSUBm46Y6vegWyXOaxk27K4U4VZMD5YByyl4mW0mblesGrpplDPB5aQZLYF0eTmkTEqrbvQsfUVBKayeOUhEv7CQFR1NVjmk1aQd1aUwb,ByftV5GX4sQq78rPvPRhSRhRh7whkokCDfGs2WpF79rxiUD3RX8Wx4OtuBjFiVg2G0M3jYB526KwbJNq4od6on7ccaRiwalyVegMaGaUQ6ffWuLp3SPjLN0rsIFszsVWYbmzdxcuw1ZPIJOnkYKUpqNPF8CkmdhrmLg5c1WW3DATU2dZfNUKM6kefZhpuuHAHSpVyFLbgDusMy0cW2isz27OOYRTQkT1Kl26T7rmGvHdbe2kXfpizFf8NfTtveie,sjLlrZv1NVDACAJprUzMV31sSxIPYbNTd1Oy0mn7o71VVpMuAiryaLsWjG2AOXnvZmB9lyGr6FiEkrP2zIl3uZzfxdvAej6vZn9qyn98BLWg1f8CV4gR2j3DW9dX3WbLOBzEP7oQHVS3hd2ngjIN8cOlfQ4U82RsZAWNUDLrakNSC4idZkSlQROvuFNbW140wuhUdJcW0nMpo4rlu2tqYZZ4JUMlpASuegzGUUo8fyvVpm4ZP23Df8npOZF8s7DL,vwQXPo3mrI1E7d4P8cJdLPpVHvzGODfB2BNr3ecuG1vM86MTPhdPArQ9D6SJwWLCsVo3drVsiDwNNb3N7CZNBniwcJ6qlARmDNT6DGNXjAog1F40T4lTvoo6vBTpNpFEdiTQ4GAgdtCuhusNF9FUU1sgAwfajUVLja8elOTwcqkbfxuf6J95WXOjCnGI2K5JsxuhIyzfcc17GjEtc2lymXfr5b7bmKlQDRwajyTQdyqQLfy507oEAGgmf8V6SaFL,0LV6WFahc9gfOuwFxYmPJXa12eZcmEej0e78cTCFtU1XHr4pZkeBUSV0rxcxwV9MGQbEBKyPjKCsHMKVIyJy2DG85YeYKUl0kAjK9YbQuWVjNuCKDU6txSua25S3QzzpzwwEIYoFZnvUJiXKYaGuRI0vt7RPVZ0yKzSPVZCFFtZExtvvUhh8JrFczPuV6wgdocf1evjEFrg0HMc7AIf3ikk7VWT6lF8YL92W9LnRTNGQqsOXMLlH05SW08W6fqgC,jfiuCglIXPpfSPfhjAQWPkae5wDWchUQ0eFxDB0hldQuTdMbnAUHS0iv4EgCrw4Co0tsGrDVIk377pOlmSZ78UjLuiJxmt1RoE7bHebuT7k8bZPri2gXhXEtBbsAEc68BiVSLPBC020Rr17HsUEJchG9P7Ui14kbp87QeMFFCZTBzeRoMV0wgN8NdD9Eq2Uew9Bjn2AyA7Kb0JDtVSHSgSbn4AI1N62dH2XcMz5V0OvQTLAcJXicFxrPlDL9KFUC,y47YnTz0XlzTJMJpA8nHG2hkgxxR83ai74ArXTXxYRvPvPE3hMnP7EDhvRy6ZfbjFV6Ke5uUbGOyFHkXs7ChbQJmkRe357d5pMQmrKLx29c9extbyRFID2xjKuVv59Gz60jruCy2j9JE5FKQc6UQe7H2yu9e50SSR3gxL6lRk45KBKy5hMTlKOuK2AtvC17i6kz0FJ9PFKrj7ekxCgG5Q6MGpjGXfAHA3U5RCpaiS7Zq3zTAqKItqq73FuZV3e8p,5nZa3WAFwmJZwjTF2vMHmDU5uNbhH6sqvhfooi171o0UQzmmJFEJhY6MrOE8pp8PANOjZQ02QD2CTHbK4DsQRgFwe3rGLitMabUaLaSbPcSNoaXb5Cv7IhmRHk6oSL8usVZTXjr7yEDa7ZVvfT4Qngy147aUo9eEfhZc077I2CnMhiQaWyM5cAHbkQzC0rBp7sDD4mOHPHWDcmgEsUvcKnbtZC0S8nC9RzFnQpKx49DzPshCzBhnMVLQGCnOheBU,3Re6XIoBvm8Kl3Vw7gAxZoDkCdnILRoAaxKUoSy3BZqB2O3e8xDdHEj6YFRYIBO9Izfjn5lB3wDvMZj3wkcjxfSHrJt9o5O20wwEOUVcUyBchnh7TutttFRghlZvTYYLRnEeYDldN2DEzaMlbZg3ksPLfXePxR3aJAcZDd4JZb8gZKhEj58B7XoD1pdhTXP76YZudO0dFxIMyMassIbW5Jb0glBRIic95jMZdvsqQtvLXJxzw2LxPqtKRbnmx1M9,xaSQVlHIG4db81z4HNE9SCMpF5WhOuWy3tZW8WCSaKL1vOhztcYobETiGq5hAlAHTCfZpQABX7Vkq4dpArTqJrm5lSRfJHKnMLhbKvxsnfcqQlDqaDuhzOSDPno9eA6JStMGQFr8mfNGdW85RGzhWOpB8fMTkLgNLPuthXSHP0ExiYa9YyrLjSqGO02VonEaZSLDjzLz2GpZEDupecOrRdcQyWEW5iZlOr2D6sbBk7Fa0xNDO2N4nZQzLOd9PBkK,2VW3dtP3ztIPxW4rOSfqbaroQwDMNGFD8pHWznWEyOaChx1J2kqSdiPLa1LsptZ54ha8SPmBEjFBjXtHc1DnvY4n3yhOr9HWzibbK8Iqfg9bFdr1UjjKSNx2SSg7pG7DiCzQwLlmp3nTAyqTBrbuKiSKPCYEfhUxVKbXLxt2jG07XqnuKOf4TbiUo3YehcJEVmRuoxnydb1QUC3Prk6tP32pc99t0GNxOenbaftX4S8YMlHWsNTVj3NaNQJQCnNF,s1YypwohwHV4wppRl49J6ZUUAg63c3F704INH1KvZaUEfnEdN5sX1TlHEXE91qGSbgqnNCJxTIPIin0OEFZgVX6rysqwCicTSzpV5PvIjvx7WgKCKyw2HRKWd3iJQBzitJ6jAaeH9c7HvHhoPEbvIoZ9j0iuWbjnnBBFUoe89a1rMzmWAseDQKe2SNHN2FYHFVsmqHSyD4VrDDeOop9WeRqANcyvvoMHGQwDYZ9rm7U2HT5CFRVeeTFZfk1bSrzK,tbskV0i4lRmK4F8TMaN1IY63NesGu9VBKZ5xCtKhBVjVM0vfRe3vole3pGhGa8NXZCECkHjSEDVFOCCjUUOKopf9xWBvMcuo3D3xMh2z4sUvPwqAG9h2MBgKAbEbTxodzX9PT5qmViOLJGOTIbLvOSD64gZ39r2r0MQIhOQmZigWM8lx7VoFrgkkB4NRMn9yRkE0IS45FLlV35lQQIN0nfvA3kyq6LlAuB4lpq4xQQYRR86xW2uLRhyoQ8wAnfzs,eM7I9Uf2mDMOixNiNci5B8kzQjLAeqCIfJPAU91Mu93qpIPXykcptboCh5ikgz0LC6cUWPRokK8GEZOgFVGrMYmADB3mBQhkx8YC7oHC6RBKwvLTHbt7Ah9Ab0Xrgyq9EleNfUmQ78LUh59hrNu3MkFzingr925x85PHmDIf0BcMWuN4h0v1th78rZyJ8ySDXaLzHPke6VQmcvsAQtwd8aI0oRLaMrVX0ne0jJqyaRWrWBkVb7WLIWO55YFsEOim,a20dHLG4fxikS5noDnBwirz7l4hnLDhiSNAACdHOW9VkzLNLwETJjLD3kAfFeACmltjnKnZw187ZARDJBSrSBneFm5za0O5o56yCLnlJoSqpT8lpeLgYf0gQATSZ6lhaM5kJpjlmo8c3An0q8nMaBgCQwWH0Uj7mzHdBOtovYw8Ucu2TzIqAynQ9pxpaRhd314IRtIZzsyniJnWqhJGLlPLKtT1Q7yVaX4FDxQwi3oXZjlI0xjlRB7wHga5ofxpw,3gHPrREWNwdnLFP9Vof6jwxSspqOiA2m70UzrxlPA3EaP1Z17gz8KPP4On78dN5W8vgfRWSuXsIX3zTWalC3TZyI8ym3sU2DAc3qc1g9sLgOx84tKaDU3eP3AzJfa0klLhJi5Kgfxo7Ska17si8aiZlW5A2YXBXbW61cRB7ryolciRDBO29PhXJVXPkHJ8jyZlZCwPOoVhqCQcRPv6iJBqPfoRTfQY4rSQhpEISuaXNWNoTOa4Ezw3ldD14DZbHJ,Mvw83vMgpxQe7DKSxjhmYFe8ETJhvpEXc6O6eJx1etvoYbxrUF89U6qkHHQuhYdMkWcxF1n7ItT9znQOL1MdlXg0t46mZj3nL6Se39rt0FcXbqonSOsAzzPfvONeTCK5Lx4L37WFi1QoFl281yw1Qmy4sK6VGE6SzcZcDnmXzEBWYaSfqwtvrAaux8YexSIH8ozXzsglWb3kdAMJ7WXVvwZky4JBugCURQVeoQMXnrVqv2zo3jvj081WsS2Cd9TQ,3WH3Ek9SfZmSRbby2kYyEacdqThTzwZeUavbXfm8Cj02w0TBZZfBqJwY7rsfSHZaNRgiqnPWr2YvGYmti9R5aQhXqxfzPDhF0NvyfKBsMiVG3tZh6sD9anotZLaMzA88KLS0vDqAwffE1YNGXjHDjWrRMnxx4ehW2pmRFqdQ0EwcukB7gPm5smai9R4tHg2XEqbNZkFkOYEhRUYeAa3LADJzNFKqDzrnCNvM70kCZ6i1fdC1CNdubVUL0NAHNRvz,Q3fP9m1HvOh5v1A0JA1iTkVfwBW7PvkTf8SSQkgUPUIXjda651wBYGMM2NehF8XRNwY71MLR98d0ThbHDgzMfFRgAPnqFYFZTV2pstnw8WamoNL9wxNJY0bGeV3NfULGy1mNrXHt552R7oepf8jaDuwruIetN3ass58RHEM4hrRxID7icLxWqTIq0u69d5utmIao0vTxaATjj4AmzhRBO644uEAikOmtRg5zEHRrqfxoizfCSXiMuZ4lLtR2Q6Xj,BEnT8KtkG1NmiNdjrvxPNdTvBg6Sf5r3JmI6PokG2a630kBIaDOiNTs6wBvsk78jF23uLzDEeaFbWKw2BtLEr00oHpoxwliJ8naUCQI5tZUBliyyjosDxUD5ncisqbyvvCbsSvrXXkx48cXSjpMuV1scUTJD7FYDiB5hlLJ7x6oEhqNyIShWn1xIKQOtHZvfSecI2erqvbpCc5lU5xAYDKE33zvWz6z77NHOswTIhclE96sY0gSyO6i8KHj1wPQF,F4dMLt6lyTzQTowU1shErbQ3MJwKTz9uKXNCIlUt3ZQvxSIwOaeoeF756MvozpXSdzvlBukGXFwdpvuteFgj4cAoumjuwbJdV4kdcipKiStcs58Ye6BAvK9dRP1OpW8493QMZSn1hw6gtFxIKVWW9UysxV6K8KmKUUjRnPQa2eFdmEgR6l0a7Ca0fmUk8b08UuguToDwsMFxDCCeTUvbLJt1BRjf9HhCo5eclfzn7EsSDvikx6kcZhtRUcajXwkG,HNWWDwESO2SGU1rFhzadCsKVyc6Q6ct6GyvrdZkv6KaXQ70jBvZ9lok22uzOim6Eh0f9VyCM4IkqyhQX4XA1RYXBvX3xWqr37HmCyS3b00u0jj3w2gLAZAH2m5g2rQzvi8PeRTjaG8tvU1ZPXGRjMrCppLroT9hGpPbqFfwFxBXB8olzYFTLg4CYhNt5EbDOW8oPHXKi8K1EupqQtUj12GReFC2RWaTNunviwtWQulSNZ03kOuLhsBCqqYhtFVCt,hYzf1179G3BSghOaeUU2IBZpgTbnMpSsXFRhw2Q2b2V3pDNyt2ZBYnMUWiM56b2oz9waSWcfiYFKeqCKGQi0Z0lK2g7iBmZgbPwANttUsFvagvg51gqAPSVFhQ9swM17PIBT1dfh9wwkT2kFxFxRaPly2qHzFjSjwNlrn6EidxTXyCkI1um74WqSlttUUzVgU2QK4MIYWdBDPCze8xodC62CFJbyPsXPTZiDaGqwELbdbdPfjCT6oH3rqD0m4qvd,10qoKc1M0HI4nOBPVJKNNyIKvsL7RxYvHD4ZOHUFBEXPtRVxVZ4vWTVCI9UoxonUqSPre6lbPyu5mZD1hw6VWX8lMGpUbAkSIIfw01Ojj8y7ZNJxQBpX50TeqCXDjj0A3LyVE1cz0j5bpq64thx6cLPwEyH3ruzsGRu16436mfjjUWOlnGYCGf6lvAZyxgpiTu9xpOCWkOchmDzIS8GL00BakvhESvDPWd9UQZvyao1c2t4q8rKHqi8GDJajEvx7,PPY1fFvcpxyANunySKY7mR9LIS6odx0OKxBFZFRGv77WuRW5RWfS60zziXfG5EpqizyHwdotwM7pycf6HMFJZYyfiP3SdYoYN5B07YwjrcZEClYfnNpcfsEDPC71UEVFNucbW3ffJfX9qMvQixjCorjSzDKvKaIuz2bsR6RyHtetpNW0guuxsmbfiKknVYcFjiwUG2Ep9wJ8ZL4QgSEaPLh5ekKNFc5DkKH64g68fBd8onpfj1es8HQRRaCRuScL,E0AC7fpzHsDG9k0BS9nlFz2QB5vAW4QzvDLhicv0VqCxwHjmKLYbi5hj5xd8jOuXZjLwPOyHzdFlk2'
2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server data flushed'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server received (16384 bytes):'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server received all data: O7MFYZxaha1EOH5n0RQNyTSTSmrad1kpXa1y1KXAS7dCdd4h6uPkxNnqqlt7BlLIET6LZ30qUqn7otiCO7oQkRXPi3uFuBT1qcyVBwfKYj6ZapnNnQY7HVNwtgJIGHU4q7wEFarn1mR0OubLYkWnaSZ7UjbFuQO6drcp2N6SSDmX9J2EH5,H67Sn4ZFWY2ttc0QQASfPCsKsYNlzQMqAY3LQIEE2ppnbiW9IYqRQ0gcQWq92xGBL6FNayoIp3yoVh50LmoLHgoWzpfwXZsbciomeCwYZHosUuylu2qPclTN0VWFSks8zntX78FPR6ahvDmrwfl40Fm46W5TVMokXrp3dgVyOLk1bexbv1S4XoRyjC9upgTY6veVVsU1tfAlwaEQEbzWpbP4Pl3bqTmvILqV2z9oFOFCh6lTiVXVPUbTA6q9jw1C,SpONcvND9GozN6Ok2pvb4U5vmbfPKKuAgeqkXliVp2tvv1t57JQOX77CTQw3c9bmveLdDpX0zuGnOsLLQonqgEVTC3gYL8590JlYaOUeKqgc6JzKa1OVMq0fFDLXxxPT9y0PBEHtiIQxRGg743CAtkD8LcTLnqipZ1OIxdDHNKv28NV5MfdeWLRyLtYPmT1fZ4Or8TH1eli0EvDabsViKNjiH2aaEMsITbBY91rcsgp12BljelW2NzSE887lhHEs,WYqWDRwHAJvNiO6xdYkWPFGCJPkr8j56H8Yiq5Hw9Y8A5loEkfdyafqBUNw755Wq5hjtprbBLe3f0Pp4rpWWYFgsRrnqBQECeMwXDYOUYrh8XRSbazwTrgumESaNJLf90JWmEoarhiBlbRWnE00DV0AjI7qxyqw496TSG7o1pIj9Bb3LBAKGOHLVH5cqmcn8Q3TRVJBS5S1mxAiKjQi4wZQnW6DxI76jh3NISOLTUEk7TdFvgbjWMf8XTUw3K16M,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:3
[ThaliCore] VirtualSocket.closeStreams() vsID:3
[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,CpDPIRJhiBneYwoQTFDvkJcBRTXPscdaej0ZMVtRlMART9yVYLgXewaj3SrqtIi7UnDXAVMtuLTwsToIUaWBdGx7ySTSZlxVwDOTbcXOTa5OhhlOBTjOqlPehmlduThDGIz2lkS3ADBQuEJSBHNDJz19lvTxBmoJ43iPgVwvUeBFJqsDodpBGAc7pMM4OcvGezklgrHR2oJb7zeET2Glwi0hgaRXZMrQyDlpVgF0L28gmJWMe9dlI33pRx8Zs6E3,MTDRGnMrG4H6MbB9uispfaR2AIyYNBLi9f4f4N2ApdAgVvBzl5Pe7AU9JPe8fjI14HR9ewMwo4epaohI6LExbaTen0OuJEbXMgzuH8MO81zMumVmLswtYvpkrc1HU8ZUMiSPjCwMT5Rer03NPG2IJMFIAKNcncRHoiXmE9I25dq0HEHRAL1ib9UdbKMDRkJk75IeZ4o9WhKWPePpTkg9PjtKsyTDAdXe4X6NBsdLf1oQTmooOGL8UEXyy5TI7tzh,k2KkQKFbBJ9a2NkZuW6nqeiCZ3dD53zsq5DQNSDsbZi6MSzpb7sQJTtO0zGqRHJZk3Xzm9sltr2HyisJfQbKpao8QMgBghN9Q5dd0dhj04e0wXy1PUFsK7XhAAY9YasWktlT1nHc2yq7zug8CCZZaQo0rcebBUKzqUqBx8KPgwVMkbeNQlVX09FQVrTIqUAfiz66D4VPx34w0pLS3ZTXELVynQlnYnFumQx5BZZXCh9zsVUFd5oKu5wNLnnhuo9N,Qg3F2iL9CejwbizmA9PNDzEkymKygJRST0XEKqRjbriC7hRalDCRWDOVZKqMzZfmKd7yEWcJHIF3svUYCDxEKupGVlpUH4NTetp4FfaW2NyoM7hijsXq1SyLrtm3yVbPgRAbn8i41Z1vFSYBM6b5kvmaClMRtNhUcnQEx9X2gsBlXD6y1AWEfhZWaXny65mJS7mTYqgaojINDdHVfAc0fPBgg9kKexRbBfUhq1mDekU3l5lyBVJRbF3PuNKSok1n,[ThaliCore] VirtualSocket exited RunLoop vsID:3
[ThaliCore] VirtualSocket.deinit vsID:3 [2, 4]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,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'
2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server sends data back to client (16384 bytes):'
,2017-07-12 13:20:05 - DEBUG testThaliMobileNative: 'Server data flushed'
,[ThaliCore] VirtualSocket.handleEventOnInputStream endEncountered vsID:4
[ThaliCore] VirtualSocket.closeStreams() vsID:4
,[ThaliCore] AdvertiserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
,[ThaliCore] VirtualSocket exited RunLoop vsID:4
[ThaliCore] VirtualSocket.deinit vsID:4 [2]
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) disconnecting:false socket error:nil
[ThaliCore] TCPClient.socketDidDisconnect(_:withError:) client disconnected
[ThaliCore] AdvertiserRelay.didSocketDisconnectHandler disconnecting:false
,[ThaliCore] Session.session(_:peer:didChange:) peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", genera,tion: 0)
2017-07-12 13:20:06 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"ETEeZqNQE287vmFfEranA2pLr3NJl57D","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:06 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'ETEeZqNQE287vmFfEranA2pLr3NJl57D', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"FD82B37D-D503-467F-9AA6-26A0F563A03B","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:06 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:20:06 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"FD82B37D-D503-467F-9AA6-26A0F563A03B","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:06 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:06 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:06 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 188FFAC5-6F17-4776-8380-760277222EAD (syncValue: wDK8zVo,Dv5ml29a5ocrbp28FBbE9seNI)'
2017-07-12 13:20:06 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:188FFAC5-6F17-4776-8380-760277222EA,D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:FD82B37D-D503-467F-9AA6-26A0F563A03B:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "FD82B37D-D503-467F-9AA6-26A0F563A03B", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56689
2017-07-12 13:20:10 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"wDK8zVoDv5ml29a5ocrbp28FBbE9seNI",,"error":null,"portNumber":56689}'
2017-07-12 13:20:10 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'wDK8zVoDv5ml29a5ocrbp28FBbE9seNI', error: 'null', listeningPort: '56689''
,Connecting to the localhost:56689
Connecting to the localhost:56689
Connecting to the localhost:56689
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:,) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore], TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
Connected to the localhost:56689
Connected to the localhost:56689
C,onnected to the localhost:56689
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:5 [2, 5]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:6 [2, 5, 6]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
[ThaliCore] S,ession.session(_:didReceive:withName:fromPeer:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:7 [2, 5, 6, 7]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,ok 109 correct string length
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 110 correct string length
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,ok 111 correct string length
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-07-12 13:20:10 - DEBUG testThaliMobileNative: 'Client data flushed'
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:2
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:2
[ThaliCore] VirtualSocket.closeStreams() vs,ID:5
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:5
[ThaliCore] VirtualSocket.deinit vsID:5 [2, 6, 7]
,ok 112 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:1
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
,[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:1
[ThaliCore] VirtualSocket.closeStreams() vsID:6
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:6
[ThaliCore] VirtualSocket.deinit vsID:6 [2, 7]
,ok 113 got the same data back
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:7
,[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:7
[ThaliCore] VirtualSocket.deinit vsID:7 [2]
,ok 114 got the same data back
,# teardown
,2017-07-12 13:20:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,[ThaliCore] Browser.stopListening()
,2017-07-12 13:20:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:20:10 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:20:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 115 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:20:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 116 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:188FFAC5-6F17-4776-8380-760277222EAD
,[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
,[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56689
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.disconnect() peer:188FFAC5-6F17-4776-8380-760277222EAD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0 state: connected -> notConnected
,[ThaliCore] Browser: session notConnected Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] BrowserRelay.closeRelay() disconnecting:true
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "188FFAC5-6F17-477,6-8380-760277222EAD", generation: 0)
,# setup
,[ThaliCore] Session.session(_:peer:didChange:) peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE state: connected -> notConnected
[ThaliCore] Advertiser: session notConnected Peer(uuid: "C8754D0C-B89C-4AEC-9174-3F312C3160A7", generation: 0)
[ThaliCore] Advertise,rRelay.closeRelay()
[ThaliCore] TCPClient.disconnectClientsFromLocalhost()
[ThaliCore] TCPClient.deinit
[ThaliCore] AdvertiserRelay.disconnectNonTCPSession()
[ThaliCore] Session.disconnect() peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
,[ThaliCore] AdvertiserRelay.deinit
[ThaliCore] Session.deinit peer:CF501BA5-CE1F-458D-ADDB-D216249B1ADE
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:20:11 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift data securely
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:B94AF845-82FA-4968-A8E5-D060BBAE3A27
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:20:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 117 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:C25B9AB7-5FF8-47F1-AA10-865CC9D6D26A
,[ThaliCore] Browser.startListening
,2017-07-12 13:20:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-12 13:20:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-07-12 13:20:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 118 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
2017-07-12 13:20:12 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"188FFAC5-6F17-4776-8380-760277222EAD","generation":0}'
2017-07-12 13:20:12 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 188FFAC5-6F17-4776-8380-760277222EAD, (syncValue: J3rNgmlNVBvtcev9OfqDbSwr9cELJcd8)'
2017-07-12 13:20:12 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", gen,eration: 0) new relay
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:188FFAC5-6F17-,4,776-8380-760277222EAD:0
[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C089239F-FC8D-476E-944D-1E38E0C79965:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C089239F-FC8D-476E-944D-1E38E0C79965", generation: 0)
[Tha,liCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
2017-07-12 13:20:12 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier,":"C089239F-FC8D-476E-944D-1E38E0C79965","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:B94AF845-82FA-4968-A8E5-D060BBAE3A27:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "B94AF845-82FA-4968-A8E5-D060BBAE3A27", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
2017-07-12 13:20:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
2017-07-12 13:20:13 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F813D69B-C593-4754-A03D-1675EBF9957D","generation":0}'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:C089239F-FC8D-476E-944D-1E38E0C79965:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "C089239F-FC8D-476E-944D-1E38E0C79965", generation: 0)
,[ThaliCore] Session.session(_:peer:didChange:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", genera,tion: 0)
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"J3rNgmlNVBvtcev9OfqDbSwr9cELJcd8","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'J3rNgmlNVBvtcev9OfqDbSwr9cELJcd8', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"188FFAC5-6F17-4776-8380-760277222EAD","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:20:17 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"188FFAC5-6F17-4776-8380-760277222EAD","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:17 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:17 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B (syncValue: YAlUITz,5ct00r9DSxybvVUCJd0bDAjNT)'
2017-07-12 13:20:17 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9,B:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0 state: notConnected -> connecting
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56701
2017-07-12 13:20:21 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"YAlUITz5ct00r9DSxybvVUCJd0bDAjNT",,"error":null,"portNumber":56701}'
2017-07-12 13:20:21 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'YAlUITz5ct00r9DSxybvVUCJd0bDAjNT', error: 'null', listeningPort: '56701''
Connecting to the localhost:56701
,[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:8 [2, 8]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
,Connected to the localhost:56701
2017-07-12 13:20:22 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
2017-07-12 13:20:22 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 119 got the same data back
# teardown
,[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote peer})
[ThaliCore] TCPListener.s,ocketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStreams() vsID:8
[ThaliCore] Browser,Relay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:8
[ThaliCore] VirtualSocket.deinit vsID:8 [2]
,2017-07-12 13:20:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
2017-07-12 13:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingSt,ateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:20:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":f,alse,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 120 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
2017-07-12 13:20:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 121 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56701
[ThaliCore] Session.disconnect,() peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "FAADB9DB-EF2B-4CE8-8BD8-233D8DC59C9B", generation: 0)
,# setup
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:20:23 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Can shift large amounts of data
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 122 Can call startUpdateAdvertisingAndListening without error
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:FC9FEBFC-3E83-4A49-89F2-A8ABC2F8250D
,[ThaliCore] Browser.startListening
,2017-07-12 13:20:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-07-12 13:20:23 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 123 Can call startListeningForAdvertisements without error
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
2017-07-12 13:20:24 - DEBUG t,haliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"F813D69B-C593-4754-A03D-1675EBF9957D","generation":0}'
,2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for F813D69B-C593-4754-A03D-1675EBF9957D (syncValue: vcle0usJBAbYW214cBCTYddIcARa5DZO)'
,2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0) new relay
,[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
,[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"188FFAC5-6F17-4776-8380-760277222EAD","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5BB2B0B7-6FBC-4A86-B83E-FA65E9B8EFCE", generation: 0)
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
2017-07-12 13:20:24 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"9281573B-540C-4F9A-8AE1-6069B66045B0","generation":0}'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:5E835EFD-E820-42F6-9814-E20DFCA52E02:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "5E835EFD-E820-42F6-9814-E20DFCA52E02", generation: 0)
2017-07-12 13:20:25 - DEBUG thaliMobileNativeTestUtils: 'We got a peer {"peerAvailable":true,"peerIdentifier":"5E835EFD-E820-42F6-9814-E20DFCA52E02","generation":0}'
,[ThaliCore] Session.session(_:peer:didChange:) peer:F813D69B-C593-4754-A03D-1675EBF9957D:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", genera,tion: 0)
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"vcle0usJBAbYW214cBCTYddIcARa5DZO","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'vcle0usJBAbYW214cBCTYddIcARa5DZO', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"F813D69B-C593-4754-A03D-1675EBF9957D","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"F813D69B-C593-4754-A03D-1675EBF9957D","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:29 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:29 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 188FFAC5-6F17-4776-8380-760277222EAD (syncValue: DZzo2eE,Kyb1QZ5LTT4TphZVXIv74gDhs)'
2017-07-12 13:20:29 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:188FFAC5-6F17-4776-8380-760277222EA,D:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0)
[ThaliCore] Session.disconnect() peer:188FFAC5-6F1,7-4776-8380-760277222EAD:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:188FFAC5-6F17-4776-8380-760277222EAD:0 state: notConnected -> notConnected
[ThaliCore] Browser: session notConnected failed to connect to Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", generation: 0),
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] Session.disconnect() peer:188FFAC5-6F17-4776-8380-760277222EAD:0
[ThaliCore] Browser: session notConnected removed relay for Peer(uuid: "188FFAC5-6F17-4776-8380-760277222EAD", genera,tion: 0)
2017-07-12 13:20:34 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"DZzo2eEKyb1QZ5LTT4TphZVXIv74gDhs","error":"Connection could not be established","portNumber":null}'
2017-07-12 13:20:34 - DEBUG thaliMobileNativeTestUtils,: 'Got multiConnectResolved -syncValue: 'DZzo2eEKyb1QZ5LTT4TphZVXIv74gDhs', error: 'Connection could not be established', listeningPort: '%s''
2017-07-12 13:20:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIden,t,ifier":"188FFAC5-6F17-4776-8380-760277222EAD","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-07-12 13:20:34 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-07-12 ,13:20:34 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"188FFAC5-6F17-4776-8380-760277222EAD","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-07-12 13:20:34 - DEBUG thaliMobileNativeWrapp,er: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:34 - ERROR thaliMobileNativeTestUtils: 'Fatal connect error: 'Connection could not be established''
2017-07-12 13:20:34 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 9281573B-540C-4F9A-8AE1-6069B66045B0 (syncValue: f6KmeVj,lbbOqA2CnjcDZ92OciXldaGDO)'
2017-07-12 13:20:34 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0) new rela,y
[ThaliCore] Browser.inviteToConnect(_:sessionConnected:sessionNotConnected:) Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] Session.init(session:identifier:connected:notConnected:) peer:9281573B-540C-4F9A-8AE1-6069B66045B,0:0
[ThaliCore] BrowserRelay.init(session:generation:createVirtualSocketTimeout:)
[ThaliCore] TCPListener.init(with:socketDisconnected:stoppedListening:)
,[ThaliCore] Session.session(_:peer:didChange:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0 state: notConnected -> connecting
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:F813D69B-C593-4754-A03D-1675EBF9957D:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "F813D69B-C593-4754-A03D-1675EBF9957D", generation: 0)
,[ThaliCore] Session.session(_:didReceiveCertificate:fromPeer:certificateHandler:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
,[ThaliCore] Session.session(_:peer:didChange:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0 state: connecting -> connected
[ThaliCore] Browser: session connected to Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] BrowserRelay,.openRelay(with:)
[ThaliCore] TCPListener.startListeningForConnections(on:connectionAccepted:completion:) port:0 localport:56711
2017-07-12 13:20:38 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"f6KmeVjlbbOqA2CnjcDZ92OciXldaGDO",,"error":null,"portNumber":56711}'
2017-07-12 13:20:38 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'f6KmeVjlbbOqA2CnjcDZ92OciXldaGDO', error: 'null', listeningPort: '56711''
,Connecting to the localhost:56711
[ThaliCore] TCPListener.socket(_:didAcceptNewSocket:)
[ThaliCore] BrowserRelay.createVirtualSocket(with:)
[ThaliCore] Session.startOutputStream(with:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
Connected to the localh,ost:56711
,[ThaliCore] Session.session(_:didReceive:withName:fromPeer:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
[ThaliCore] VirtualSocket.init(inputStream:outputStream:) vsID:9 [2, 9]
[ThaliCore] BrowserRelay.didOpenVirtualSocketStreamsHandler
2017-07-12 13:20,:38 - DEBUG testThaliMobileNative: 'Client sends data (65536 bytes):'
,2017-07-12 13:20:38 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 124 got the same data back
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) accepted socket error:Optional(Error Domain=GCDAsyncSocketErrorDomain Code=7 "Socket closed by remote peer" UserInfo={NSLocalizedDescription=Socket closed by remote pe,er})
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) socket removed, count:0
[ThaliCore] BrowserRelay.didSocketDisconnectHandler
[ThaliCore] BrowserRelay.didSocketDisconnectHandler socket removed, count:0
[ThaliCore] VirtualSocket.closeStream,s() vsID:9
[ThaliCore] BrowserRelay.didCloseVirtualSocketStreamsHandler disconnecting:false
[ThaliCore] VirtualSocket exited RunLoop vsID:9
[ThaliCore] VirtualSocket.deinit vsID:9 [2]
,# teardown
,2017-07-12 13:20:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-12 13:20:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-07-12 13:20:38 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,[ThaliCore] Advertiser.stopAdvertising()
,2017-07-12 13:20:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 126 Should be able to call stopAdvertisingAndListening in teardown
,[ThaliCore] BrowserManager.disconnect peer:9281573B-540C-4F9A-8AE1-6069B66045B0
[ThaliCore] BrowserRelay.closeRelay() disconnecting:false
[ThaliCore] TCPListener.stopListeningForConnectionsAndDisconnectClients() port:56711
[ThaliCore] Session.disconnect,() peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
[ThaliCore] TCPListener.socketDidDisconnect(_:withError:) listening socket error:nil
,[ThaliCore] Session.session(_:peer:didChange:) peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0 state: connected -> notConnected
[ThaliCore] Browser: session notConnected Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] Browser: s,ession notConnected removed relay for Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
,# setup
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# We do not emit peerAvailabilityChanged events until one of the start methods is called
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "38EDEFA8-28A4-4FDC-B329-3F9DA3DBC7DB", generation: 0)
[ThaliCore] Advertiser.startAdvertising with peerID:38EDEFA8-28A4-4FDC-B329-3F9DA3DBC7DB
2017-07-12 1,3:20:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-07-12 13:20:41 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not matc,h with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (w,as in stopped state).'
ok 127 Ready to advertise
[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:EAEE980B-65EE-4AC6-8263-EF2B7AD64B4A
[ThaliCore] Browser.startListening
2017-07,-,12 13:20:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-07-12 13:20:41 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not ma,tch with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate ,(was in stopped state).'
ok 128 Ready to listen
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:C25CD1F9-CA63-4B0C-9A5A-335781DF371B:0
2017-07-12 13:20:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "C25CD1F9-CA63-4B0C-9A5A-335781DF371B", generation: 0)
2017-07-12 13:20:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({",started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-07-12 13:20:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped sta,te).'
ok 129 stop ads worked
[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-12 13:20:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 130 test stop worked
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:45 - INFO thaliMobile: 'Filter,ed out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdve,rtisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in tea,rdown
,# setup
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# Test updating advertising and parallel data transfer
,2017-07-12 13:20:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 133 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 134 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# discoveryAdvertisingStateUpdateNonTCP is called
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:144F395C-6FA2-4C56-9FB0-1A11D7C8926D
,[ThaliCore] Browser.startListening
,ok 135 discoveryActive should be false
,ok 136 advertisingActive should be true
,[ThaliCore] AdvertiserManager.startUpdateAdvertisingAndListening(onPort:errorHandler:) Peer(uuid: "44B69B99-2FA2-4509-8F9B-6F764F301CBA", generation: 0)
,[ThaliCore] Advertiser.startAdvertising with peerID:44B69B99-2FA2-4509-8F9B-6F764F301CBA
,ok 137 discoveryActive should be false
,ok 138 advertisingActive should be true
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,ok 139 discoveryActive should be false
,ok 140 advertisingActive should be true
,[ThaliCore] AdvertiserManager.stopAdvertising()
[ThaliCore] Advertiser.stopAdvertising()
,ok 141 discoveryActive should be false
,ok 142 advertisingActive should be true
,ok 143 Can call startListeningForAdvertisements without error
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,ok 144 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,ok 145 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# cannot call connect when start listening for advertisements is not active
,2017-07-12 13:20:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 146 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 147 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# Get error when trying to double connect to a peer on Android
,2017-07-12 13:20:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 148 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 149 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-07-12 13:20:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 150 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 151 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-07-12 13:20:46 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 152 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 153 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-07-12 13:20:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 154 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 155 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-07-12 13:20:47 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
ok 156 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
ok 157 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-07-12 13:20:47 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
2017-07-12 13:20:47 - INFO thaliMobile: 'Filtered out ,networkChangedNonTCP (was in stopped state).'
2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to nat,ive'
2017-07-12 13:20:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect when start listening for advertisements is not active
,ok 158 Got null as expected
,[ThaliCore] BrowserManager.connectToPeer(_:syncValue:completion:) peer:0d92f868-fed5-44cf-8815-95c44bfb53bb error: startListeningNotActive
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"91frl1NyxM9LUZCKxRrGWtkZ4XG8MNVZ","error":"startListeningForAdvertisements is not active","portNumber":null}'
,ok 159 Should only get called after multiConnect returned
,ok 160 SyncValue matches
,ok 161 Got right error
,ok 162 listeningPort is null
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0d92f868-fed5-44cf-8815-95c44bfb53bb","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"0d92f868-fed5-44cf-8815-95c44bfb53bb","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 163 Should be able to call stopListeningForAdvertisements in teardown
,[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 164 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# cannot call multiConnect with illegal peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:3C177070-0965-4FD1-A90A-6F623D981203
[ThaliCore] Browser.startListening
2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'disc,overyAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 165 No error on starting
,ok 166 Got null as expected
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"5TWBw9BonFtZ9EceirSQly9U6Wk3uNtN","error":"Illegal peerID","portNumber":null}'
,ok 167 Should only get called after multiConnect returned
,ok 168 SyncValue matches
,ok 169 Got right error
,ok 170 listeningPort is null
,# teardown
,[ThaliCore] BrowserManager.stopListeningForAdvertisements()
[ThaliCore] Browser.stopListening()
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
,ok 171 Should be able to call stopListeningForAdvertisements in teardown
[ThaliCore] AdvertiserManager.stopAdvertising()
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 172 Should be able to call stopAdvertisingAndListening in teardown
,# setup
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"10:b2:a9:43:f2:f7","bluetoothLowEnergy":"on"}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# multiConnect properly fails on legal but non-existent peerID
,[ThaliCore] BrowserManager.startListeningForAdvertisements
,[ThaliCore] Browser.init(serviceType:foundPeer:lostPeer:) peer:114F80B0-F193-4DCD-96D7-AFBD5DE9F847
,[ThaliCore] Browser.startListening
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-07-12 13:20:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 173 No error on starting
,ok 174 Got null as expected
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"qT6wm0H2QksFcjvtcN7FiOJ1ChSkHUbg","error":"Peer is unavailable","portNumber":null}'
,ok 175 Should only get called after multiConnect returned
,ok 176 SyncValue matches
,not ok 177 Got right error
  ---
,    operator: equal
,    expected: 'Connection could not be established'
,    actual:   'Peer is unavailable'
,  ...
,ok 178 listeningPort is null
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"b8bd5b30-26e9-471d-a450-ff7f2aa632c9","peerAvailable":false,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"b8bd5b30-26e9-471d-a450-ff7f2aa632c9","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-07-12 13:20:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:20:48 - ERROR CoordinatedClient: 'test failed, name: 'multiConnect properly fails on legal but non-existent peerID''
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - skip'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - another skip'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can connect to a remote peer'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data via parallel connections'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift data securely'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can shift large amounts of data'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - We do not emit peerAvailabilityChanged events until one of the start methods is called'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Test updating advertising and parallel data transfer'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - discoveryAdvertisingStateUpdateNonTCP is called'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - cannot call connect when start listening for advertisements is not active'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Get error when trying to double connect to a peer on Android'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect when start listening for advertisements is not active'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - cannot call multiConnect with illegal peerID'
,2017-07-12 13:20:48 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - multiConnect properly fails on legal but non-existent peerID, error: 'Error: test failed, name: 'multiConnect properly fails on legal but non-existent peerID'', stack: 'Coordina,tedClient.prototype._processEvent/</</endHandler/<@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:463:22
tryCatcher@/private/var/containers/Bundle/Application/C164F135-1028,-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
module.exports/Promise.prototype._settlePromiseFromHandler@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jx,core/node_modules/bluebird/js/release/promise.js:510:13
module.exports/Promise.prototype._settlePromise@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:5,67:13
module.exports/Promise.prototype._settlePromise0@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
module.exports/Promise.prototype._settleProm,ises@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
2017-07-12 13:20:48 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios,''
,# teardown
,2017-07-12 13:20:49 - DEBUG CoordinatedClient: 'all tests completed'
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
2017-07-12 13:21:00 - DEBUG t,haliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"9281573B-540C-4F9A-8AE1-6069B66045B0","generation":0}]'
2017-07-12 13:21:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availa,bility changed event with {"peerAvailable":true,"peerIdentifier":"9281573B-540C-4F9A-8AE1-6069B66045B0","generation":0}'
2017-07-12 13:21:00 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started sta,te'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9281573B-540C-4F9A-8AE1-6069B66045B0:0
,[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9281573B-540C-4F9A-8AE1-6069B66045B0", generation: 0)
,2017-07-12 13:23:48 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":false,"peerIdentifier":"9281573B-540C-4F9A-8AE1-6069B66045B0","generation":0}]'
,2017-07-12 13:23:48 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":false,"peerIdentifier":"9281573B-540C-4F9A-8AE1-6069B66045B0","generation":0}'
,2017-07-12 13:23:48 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-07-12 13:24:03 - DEBUG CoordinatedClient: 'test client disconnected'
2017-07-12 13:24:03 - DEBUG CoordinatedClient: 'test client failed'
2017-07-12 13:24:03 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: run failed, test: 'multiC,onnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: '[{"uuid":"3e2a27fd-55aa-45fe-9813-64f7b6e4a161"},{"uuid":"71182d4e-e0a7-4da3-bc25-0736825c855f"},{"uuid":"f57f1c,14-6a15-4d78-99d7-2450f7d50b44"}]', received data: '{"success":false}'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:,27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/C164F135,-,1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/socket.i,o-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-07-12 13:24:03 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
2017-07-12 13:24:03 - ERROR runTests: 'Error: run failed, test: 'multiConnect properly fails on legal but non-existent peerID', event: 'run_multiConnect properly fails on legal but non-existent peerID', sent data: '[{"uuid":"3e2a27fd-55aa-45fe-9813-64f7b6e4a161"},{"uuid":"71182d4e-e0a7-4da3-bc25-0736825c855f"},{"uuid":"f57f1c14-6a15-4d78-99d7-2450f7d50b44"}]', received data: '{"success":false}'
CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:292:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/C164F135-1028-4D06-9DB5-29CF55F42306/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototyp
```
