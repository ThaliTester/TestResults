#### Test 1133518510ecaa77_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1133518510ecaa77/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/1320E942-F9C2-4BDA-9DD8-D8B771E50D79/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/1320E942-F9C2-4BDA-9DD8-D8B771E50D79/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1133518510ecaa77/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1133518510ecaa77/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52153"
,(lldb)     command script import "/tmp/1320E942-F9C2-4BDA-9DD8-D8B771E50D79/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
(lldb) ,JXcore engine is ready
,Starting JXcore engine
(lldb) ,Platform ios
Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-05-25 10:03:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-25 10:03:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-25 10:03:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-25 10:03:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-25 10:03:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-25 10:03:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-25 10:03:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-05-25 10:03:34 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
(lldb) ,Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.653788089752197
,2017-05-25 10:03:34 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
(lldb) ,2017-05-25 10:03:34 - WARN testUtils: 'myNameCallback not set!'
,2017-05-25 10:03:37 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-25 10:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-25 10:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
(lldb) ,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
(lldb) ,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
(lldb) ,2017-05-25 10:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
(lldb) ,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
(lldb) ,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
(lldb) ,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
(lldb) ,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
(lldb) ,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
(lldb) ,2017-05-25 10:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-25 10:03:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-05-25 10:03:41 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-05-25 10:03:41 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
,2017-05-25 10:03:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:03:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:03:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:03:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:03:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:04:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:04:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:04:11 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-05-25 10:04:11 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-05-25 10:09:05 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-05-25 10:09:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:09:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-4,0FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/nod(lldb) ,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:09:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:09:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:09:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:09:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:09:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:09:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:09:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:10:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:10:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:10:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:10:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:10:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:10:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:10:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:10:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:10:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:10:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:11:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:11:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:11:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:11:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:11:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:11:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:11:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:12:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:12:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:12:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:12:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:12:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:12:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:12:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:13:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:13:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:13:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:13:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:13:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:13:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:13:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:14:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:14:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:14:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:14:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:14:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:14:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:14:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:15:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:15:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:15:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:15:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:15:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:15:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:15:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:16:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:16:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:16:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:16:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:16:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:16:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:16:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:17:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:17:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:17:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:17:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:17:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:17:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:17:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:18:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:18:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:18:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:18:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:18:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:18:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:19:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:19:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:19:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:19:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:19:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:19:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:19:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:20:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:20:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:20:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:20:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:20:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:20:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:20:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:21:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:21:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:21:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:21:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:21:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:21:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:21:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:22:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:22:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:22:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:22:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:22:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:22:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:22:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:23:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:23:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-25 10:23:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:23:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:23:28 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:23:28 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-25 10:23:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40F(lldb) ,C-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-25 10:23:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/9CB22498-602A-40FC-BE2D-55F89969ACE0/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) 
```
