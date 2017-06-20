#### Test 126503734d7519e7_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/126503734d7519e7/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/CD6F19E4-A9A4-4A48-B60E-8101C70A2507/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CD6F19E4-A9A4-4A48-B60E-8101C70A2507/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/126503734d7519e7/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/126503734d7519e7/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64568"
,(lldb)     command script import "/tmp/CD6F19E4-A9A4-4A48-B60E-8101C70A2507/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
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
(lldb) ,JXcore engine is started
,2017-06-20 11:35:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-20 11:35:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-20 11:35:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-20 11:35:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-20 11:35:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-20 11:35:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-20 11:35:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
(lldb) ,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
(lldb) ,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
(lldb) ,AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
(lldb) ,Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
(lldb) ,AppContextTests.test_connectReturnValueCorrect finished
,AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-06-20 11:35:39 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.369139075279236
,2017-06-20 11:35:39 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
(lldb) ,2017-06-20 11:35:39 - WARN testUtils: 'myNameCallback not set!'
,2017-06-20 11:35:42 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-20 11:35:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
(lldb) ,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-20 11:35:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-20 11:35:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-20 11:35:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-20 11:35:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-06-20 11:35:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-20 11:35:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-20 11:35:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-06-20 11:35:45 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-06-20 11:35:45 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-06-20 11:35:45 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
,2017-06-20 11:35:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:35:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:35:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:35:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:35:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:36:01 - DEBUG CoordinatedClient: 'reconnected to the test server'
2017-06-20 11:36:01 - DEBUG CoordinatedClient: 'connected to the test server'
(lldb) ,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-20 11:36:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-06-20 11:36:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-06-20 11:36:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
(lldb) ,# setup
,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-06-20 11:36:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-06-20 11:37:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-06-20 11:37:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-06-20 11:38:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-06-20 11:38:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
(lldb) ,ok 4 should be equal
ok 5 should be equal
ok 6 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
(lldb) ,ok 13 should be equal
,ok 14 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# enqueue and run in order
(lldb) ,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
(lldb) ,ok 18 secondPromise setTimeout
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
(lldb) ,ok 32 fourth
ok 33 second
ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
# teardown
(lldb) ,# setup
(lldb) ,# queues handled independently
(lldb) ,ok 40 all short operations completed before the long resolves
# teardown
(lldb) ,# setup
(lldb) ,# enqueued function are always executed asynchronously
(lldb) ,2017-06-20 11:42:24 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-06-20 11:42:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:42:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:42:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:42:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-20 11:42:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:42:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:42:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:42:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:42:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:42:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:43:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:43:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-20 11:43:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:43:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:43:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:43:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-20 11:43:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:43:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:43:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40C(lldb) ,D-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-20 11:43:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/77CA00C7-2C90-40CD-9625-8FB79A1391CD/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-20 11:44:20 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-20 11:44:20 - DEBUG CoordinatedClient: 'test client failed'
2017-06-20 11:44:20 - ERROR CoordinatedClient: 'reconnect_er(lldb) ,ror error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-20 11:44:20 - DEBUG CoordinatedClient: 'test client failed'
,2017-06-20 11:44:20 - DEBUG CoordinatedClient: '20000'
2017-06-20 11:44:20 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-06-20 11:44:20 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
(lldb) 
```
