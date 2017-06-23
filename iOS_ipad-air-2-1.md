#### Test 127198710fdd070d_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/127198710fdd070d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/46B6227A-D562-45CF-89AB-1D584DDB2D90/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/46B6227A-D562-45CF-89AB-1D584DDB2D90/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/127198710fdd070d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/127198710fdd070d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:54805"
,(lldb)     command script import "/tmp/46B6227A-D562-45CF-89AB-1D584DDB2D90/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
,JXcore engine is started
(lldb) ,2017-06-23 13:09:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-23 13:09:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-23 13:09:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-23 13:09:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-23 13:09:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-23 13:09:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-23 13:09:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
(lldb) ,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
,AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,[ThaliCore] Advertiser.startAdvertising with peerID:71B3E222-4E5F-451E-86DF-64BC76761A66
(lldb) ,Optional(true)
Optional(false)
(lldb) ,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,[ThaliCore] BrowserManager.startListeningForAdvertisements
(lldb) ,[ThaliCore] Browser.startListening
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,[ThaliCore] BrowserManager.startListeningForAdvertisements
[ThaliCore] Browser.startListening
(lldb) ,[ThaliCore] Advertiser.startAdvertising with peerID:9A57BD66-4DCD-4046-ABA7-43D5944079A9
,[ThaliCore] Browser.browser(_:foundPeer:withDiscoveryInfo:) found peer:9A57BD66-4DCD-4046-ABA7-43D5944079A9:0
(lldb) ,[ThaliCore] BrowserManager.foundPeerHandler peer:Peer(uuid: "9A57BD66-4DCD-4046-ABA7-43D5944079A9", generation: 0)
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
(lldb) ,AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-06-23 13:09:53 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
(lldb) ,Number of passed tests:  13
,Number of failed tests:  0
Number of ignored tests:  0
(lldb) ,Total duration:  1.311509907245636
,2017-06-23 13:09:53 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
(lldb) ,2017-06-23 13:09:53 - WARN testUtils: 'myNameCallback not set!'
,[ThaliCore] Browser.browser(_:lostPeer:) lost peer:9A57BD66-4DCD-4046-ABA7-43D5944079A9:0
[ThaliCore] BrowserManager.lostPeerHandler peer:Peer(uuid: "9A57BD66-4DCD-4046-ABA7-43D5944079A9", generation: 0)
(lldb) ,2017-06-23 13:09:55 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-23 13:09:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-23 13:09:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
(lldb) ,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
(lldb) ,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-23 13:09:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-23 13:09:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-06-23 13:09:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-06-23 13:09:59 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
(lldb) ,2017-06-23 13:09:59 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-06-23 13:09:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-23 13:10:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-452(lldb) ,7-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-23 13:10:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,(lldb) ,pplication/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-23 13:10:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-452(lldb) ,7-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-23 13:10:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-23 13:10:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-452,7-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-23 13:10:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-23 13:10:25 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-06-23 13:10:25 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-23 13:11:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
,2017-06-23 13:11:08 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-06-23 13:11:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-06-23 13:11:41 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-06-23 13:11:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-06-23 13:11:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-06-23 13:12:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-06-23 13:12:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
(lldb) ,ok 4 should be equal
ok 5 should be equal
,ok 6 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
(lldb) ,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
,ok 14 should be equal
,# teardown
,# setup
(lldb) ,# enqueue and run in order
(lldb) ,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
(lldb) ,# teardown
,# setup
(lldb) ,# enqueueAtTop and run backwards
(lldb) ,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
(lldb) ,# teardown
,# setup
(lldb) ,# mix enqueue and enqueueAtTop
(lldb) ,ok 31 fourth
,ok 32 fourth
ok 33 second
ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
# teardown
(lldb) ,2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-06-23 13:14:17 - INFO(lldb) , CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call (lldb) ,of onCheckpointReached handler on a single db change'
2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-06-23 13:14:17 - INFO CoordinatedClient: '***T,EST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler (lldb) ,on multiple db changes that are out of the checkpoints plugin delay interval'
2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: pas,sed - test defaultAdapter'
(lldb) ,2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
(lldb) ,2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
(lldb) ,2017-06-23 13:14:17 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - mix enqueue and enqueueAtTop, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/Thal,iTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:49(lldb) ,:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/D1D7A471-2BFE-4527-B374-A82579612E64/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-06-23 13:14:17 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
(lldb) ,2017-06-23 13:14:34 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-06-23 13:14:55 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-23 13:14:55 - DEBUG CoordinatedClient: 'test client failed'
2017-06-23 13:14:55 - ERROR CoordinatedClient: 'reconnect_er(lldb) ,ror error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-23 13:14:55 - DEBUG CoordinatedClient: 'test client failed'
,2017-06-23 13:14:55 - DEBUG CoordinatedClient: '20000'
2017-06-23 13:14:55 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-06-23 13:14:55 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'(lldb) 
```
