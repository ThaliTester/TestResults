#### Test 122449695f36eb0f_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/122449695f36eb0f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/31F816A3-0281-41E7-A913-C31548FC48F1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/31F816A3-0281-41E7-A913-C31548FC48F1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/122449695f36eb0f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/122449695f36eb0f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62891"
,(lldb)     command script import "/tmp/31F816A3-0281-41E7-A913-C31548FC48F1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
(lldb) ,Platform ios
Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-06-01 14:26:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-01 14:26:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-01 14:26:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:26:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:26:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:26:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:26:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
(lldb) ,AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-06-01 14:26:18 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.30575305223465
(lldb) ,2017-06-01 14:26:18 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
,2017-06-01 14:26:18 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-06-01 14:26:21 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-01 14:26:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-01 14:26:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-01 14:26:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-01 14:26:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-01 14:26:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-01 14:26:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-01 14:26:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-01 14:26:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-01 14:26:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-01 14:26:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-01 14:26:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-06-01 14:26:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-06-01 14:26:24 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
(lldb) ,appEnteredForeground wasn't registered
,2017-06-01 14:26:24 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-06-01 14:26:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-486,5-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-01 14:26:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-486(lldb) ,5-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:26:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-01 14:26:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-486(lldb) ,5-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:26:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-01 14:26:40 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-06-01 14:26:40 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-01 14:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-06-01 14:27:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-06-01 14:27:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
(lldb) ,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-06-01 14:27:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-06-01 14:27:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-06-01 14:28:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-06-01 14:28:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-06-01 14:28:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
(lldb) ,ok 4 should be equal
ok 5 should be equal
ok 6 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
(lldb) ,ok 12 should be equal
,ok 13 should be equal
(lldb) ,ok 14 should be equal
,# teardown
(lldb) ,# setup
,# enqueue and run in order
(lldb) ,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
(lldb) ,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
,# teardown
(lldb) ,# setup
,# enqueueAtTop and run backwards
(lldb) ,ok 24 thirdPromise - first to run
(lldb) ,ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
,# teardown
(lldb) ,# setup
(lldb) ,# mix enqueue and enqueueAtTop
(lldb) ,ok 31 fourth
,ok 32 fourth
ok 33 second
ok 34 secondPromise - in then
(lldb) ,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
# teardown
,# setup
(lldb) ,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
(lldb) ,# setup
(lldb) ,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
ok 42 executors is called
(lldb) ,# teardown
,# setup
(lldb) ,# exceptions in the executor are properly handled
(lldb) ,ok 43 got expected error
(lldb) ,# teardown
,# setup
(lldb) ,# basic
(lldb) ,ok 44 sane
(lldb) ,# teardown
,# setup
(lldb) ,# another
(lldb) ,ok 45 sane
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox spy
(lldb) ,2017-06-01 14:30:28 - DEBUG testTests: 'test spy method for global sinon sansbox'
,ok 46 test sandbox spy works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub
(lldb) ,ok 47 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub override
,ok 48 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox mock
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox restore after test end
(lldb) ,ok 49 test restore
(lldb) ,# teardown
,# setup
(lldb) ,# can pass data in setup
(lldb) ,ok 50 test participant has uuid
ok 51 participant data matches
ok 52 test participant has uuid
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
(lldb) ,# teardown
,# setup
(lldb) ,# Correctly parses/stringifies USN
(lldb) ,ok 57 correctly parses USN string
ok 58 throws if usn has invalid prefix
ok 59 throws if usn has invalid identifier format
ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
(lldb) ,# teardown
,# setup
(lldb) ,# onPeerLost calls jxcore
(lldb) ,2017-06-01 14:32:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-01 14:32:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# onPeerDiscovered calls jxcore
(lldb) ,2017-06-01 14:32:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-06-01 14:32:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-01 14:32:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-01 14:32:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:32:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-01 14:32:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-01 14:32:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:32:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:32:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-06-01 14:32:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-01 14:32:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:32:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
2017-06-01 14:32:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01, 14:32:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-06-01 14:32:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-01 14:32:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:32:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:32:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-01 14:32:53 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:32:53 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-01 14:32:53 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:32:53 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:32:53 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:32:53 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:32:53 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:32:53 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-06-01 14:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-01 14:33:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:33:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-01 14:33:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-06-01 14:33:08 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
,2017-06-01 14:33:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:33:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:33:28 - INFO thal(lldb) ,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:33:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-06-01 14:33:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-01 14:33:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Can call stopListeningForAdvertisements without error
2017-06-01 14:33:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:33:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-06-01 14:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-01 14:34:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:34:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:34:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-01 14:34:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:34:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-01 14:34:07 -(lldb) , DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:34:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-01 14:34:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-01 14:34:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:34:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:34:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-06-01 14:34:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:34:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:34:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
2017-06-01 14:34:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06(lldb) ,-01 14:34:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 75 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-01 14:34:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:34:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-01 14:34:28 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:34:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-06-01 14:34:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:34:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:34:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
2017-06-01 14:34:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-(lldb) ,01 14:34:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,,"networkType":null}})'
(lldb) ,2017-06-01 14:34:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
(lldb) ,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-06-01 14:34:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-06-01 14:34:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:34:45 - DEBUG thaliMobil(lldb) ,eNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:34:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopA,dvertisingAndListening in teardown
2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered (lldb) ,to native'
,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:34:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-06-01 14:34:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-01 14:34:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
2017-06-01 14:34:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStat,eUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:34:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-06-01 14:35:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-01 14:35:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:35:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:35:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-01 14:35:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:35:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-01 14:35:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:35:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-01 14:35:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-01 14:35:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:35:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:35:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# peerAvailabilityChange is called
(lldb) ,2017-06-01 14:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:35:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
2017-06-01 14:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-01(lldb) , 14:35:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-06-01 14:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,ok 88 peers must be an array
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
(lldb) ,# teardown
,2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-06-01 14:35:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-06-01 14:35:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:35:06 - DEBUG thaliMobil(lldb) ,eNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:35:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopA,dvertisingAndListening in teardown
2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered(lldb) , ,to native'
(lldb) ,2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-01 14:35:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can connect to a remote peer
(lldb) ,2017-06-01 14:35:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:35:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:35:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
2017-06-01 14:35:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
(lldb) ,2017-06-01 14:35:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-06-01 14:35:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-01 14:35:14 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"6A7D0202-59CA-4E59-8C46-0865525B1538","generation":0}]'
2017-06-01 14:35:14 - DEBUG thaliMobileNativeTestUtils: 'Issui(lldb) ,ng multiConnect for 6A7D0202-59CA-4E59-8C46-0865525B1538 (syncValue: 59ctDW9HdkVT0hrw7NIEOg4vfyqrzbV7)'
2017-06-01 14:35:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,2017-06-01 14:35:14 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"ACB251AD-2F01-4226-AE25-91E62AFB2CC8","generation":0}]'
(lldb) ,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
(lldb) ,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
,2017-06-01 14:35:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"59ctDW9HdkVT0hrw7NIEOg4vfyqrzbV7","error":null,"portNumber":50743}'
(lldb) ,2017-06-01 14:35:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '59ctDW9HdkVT0hrw7NIEOg4vfyqrzbV7', error: 'null', listeningPort: '50743''
,2017-06-01 14:35:17 - INFO testThaliMobileNative: ''
(lldb) ,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
ok 99 listening port should not be 0
(lldb) ,# teardown
,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
(lldb) ,2017-06-01 14:35:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-06-01 14:35:18 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-01 14:35:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 100 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-01 14:35:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 101 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:35:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can shift data
(lldb) ,2017-06-01 14:35:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:35:22 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:35:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 102 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-06-01 14:35:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-06-01 14:35:22 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre(lldb) ,t":null,"networkType":null}})'
,2017-06-01 14:35:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-01 14:35:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C8722851-9FAB-4C3E-86FB-E80E6EE920D2 (syncValue: k3POlwRKj1c4w0fQaW2bCBZn5P0DexJx)'
,2017-06-01 14:35:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
(lldb) ,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
(lldb) ,2017-06-01 14:35:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"k3POlwRKj1c4w0fQaW2bCBZn5P0DexJx","error":null,"portNumber":50749}'
(lldb) ,2017-06-01 14:35:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'k3POlwRKj1c4w0fQaW2bCBZn5P0DexJx', error: 'null', listeningPort: '50749''
,Connecting to the localhost:50749
(lldb) ,Connected to the localhost:50749
,2017-06-01 14:35:24 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
(lldb) ,2017-06-01 14:35:24 - DEBUG testThaliMobileNative: 'Client data flushed'
,ok 104 got the same data back
(lldb) ,# teardown
,2017-06-01 14:35:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-06-01 14:35:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
2017-06-01 14:35:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 105 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-01 14:35:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 106 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:35:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can shift data via parallel connections
,2017-06-01 14:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 107 Can call startUpdateAdvertisingAndListening without error
2017-06-01 14:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-(lldb) ,01 14:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,,(lldb) ,"networkType":null}})'
2017-06-01 14:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,2017-06-01 14:35:26 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for C8722851-9FAB-4C3E-86FB-E80E6EE920D2 (syncValue: UIbvicRo55yHvaJNzhQVNQHHByjO37Nc)'
2017-06-01 14:35:26 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
20(lldb) ,17-06-01 14:35:26 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"UIbvicRo55yHvaJNzhQVNQHHByjO37Nc","error":null,"portNumber":50749}'
2017-06-01 14:35:26 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'UIb,vicRo55yHvaJNzhQVNQHHByjO37Nc', error: 'null', listeningPort: '50749''
(lldb) ,Connecting to the localhost:50749
Connecting to the localhost:50749
Connecting to the localhost:50749
,Connected to the localhost:50749
Connected to the localhost:50749
Connected to the localhost:50749
(lldb) ,ok 109 correct string length
,2017-06-01 14:35:26 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
(lldb) ,ok 110 correct string length
,2017-06-01 14:35:26 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
(lldb) ,ok 111 correct string length
,2017-06-01 14:35:26 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
(lldb) ,2017-06-01 14:35:26 - DEBUG testThaliMobileNative: 'Client data flushed'
(lldb) ,2017-06-01 14:35:26 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-06-01 14:35:26 - DEBUG testThaliMobileNative: 'Client data flushed'
(lldb) ,not ok 112 got the same data back
  ---
    operator: equal
    expected:
(lldb) ,      'PUV2cA3Az2g0ucovQW2Ay3NEr8cv0cAt5uBoINBcF2BZaXql9rkGTLzUK64l4ccaWPMiHJn7rv3V6FP6shhe5JR9AJHuPCNejyBJQOd3WCuUqaZy5x2jsg8ueNZw9qokX3DWvPwPFfTHfLCbiBAC9XHwrmLYmqquuDtGt7TsSx7YdNJ8pYuZgKDCQPx9pAdAA9oXShmRXgburLWGHooDLrul4TlehJhmTSHKTujw61MwC1taF9WcW9ymu,XjATNZaauiOCTYe5yGP8vTmX2EjgeJbRkPgOEml8GLuv76QyQ9GY4Hg7Ac7svjHyfZyYEIobkOB8ONsFEBQokCHBAyt9BPUhvkdHqJW3ycwVvzrrnddVOItwCp9sz5n0HK7UeY7obpFl9Hgopg5OZWdk4WyPKtbB1wPGHAyVuAPd4ldqvejeMGzq6Sewzpd7qtBCkhbr3KwSRwVCjUhxvxZK07cpPYx9WTldmBKL2qoS1vAEM12CB2dLowMAfy8G(lldb) ,4pdYzHaJ6uS4R6GU9sSvwaRwfxsrCSwm2FIAVzn9GHlpsXAEpFo8qzuHQGeKF8JOJg0sfJYjZBWTrVum45jVXvtJlU06c4OKuZqXyIL6VzLAK3ko0mwhLK5iwyZof0M2SxaIr3xFZuKQk4XjrlUeEQQVPYERRBLLtTqgFghKJqqST08kyqT7BUtlrjBnUm7dyGWMfhuiyI8ctwIuhNHq4nMRy7NBavnJc5HfqfPHAZ2nGeD40Ls9EFD1Q2v9h8An,toVP5XKvdKY7rC09UIemAYVhnWFnci7yzOKEtIQl9xknr0vbTwKmSAsn1NbMrIFPzb4NDt1mbcoW5oMXnxm02klofxeaMCwd00Tbsr2dsOrWNwcTLc0N7npKvQ3TXzdEejvzp2hRmjyWuFvFlHeSgaEbnMi670gPR47GIG1Tzb0proNy1s8YQZ4SWrhqaHUzyl2f25ddZBPDJisNxdRk10ygUX6CsXbdyrzw0q4gi9pHzHnvGDexEQUUz0EnNRko(lldb) ,HHKGyH68OxTv30RwqtgDfxlMCgSukq8bUNUjGjB5ON23qWLd0JFzG6lCLAjZQrLH74Vg4w1dWBRvYL3vQbtIoCCJNCe58c0YERl18mlJCbB8k25kMkdcHb5UHWYu1FKIagUNK7UYEcWRLjga3j8JAWCOYqwoKf3ptn3RbZrPVSB4X6tNLEj5AuaBXJeozEroVfcJs3S6B5tbRljt29wvAz4Xiw0chfpJrzsCQk2UGuGQEUk8EiROd86uUKA05wsO,kFcdWyMXmviL3fl8zMUAGGgynUCNu3JY9ot0z48rANwMJsF8sWM51CTPgfkJ7GouH0pGP1g8a0jSKDeVAgbjAvFSTr0xGMERrYQF4FtBILsl2N21KPL3owwTxPeUNMDppmZs1NJEiRzoM2nK3DK0BzZo2uwNRWxiGiYWsC5oBtkKZw0XVGUs5Mv145sJP3unKK7J8CSXQtX8UzEhqjyGWabKMXyBGVlKSqI2Zouy5Aq8Veb06QSjLokMsZsigNbt(lldb) ,OUBRKbTISJ6NotYFlzw2f1xFzlV4dOHp6VUCzTRA8x9t3z2BPHuMBodmw48oI0IFOgLUCZ0J0hcPnY2UQGI4tKqGPvUGZ8BujujFlKqPziGHb2tJzLtwHzxGMe2eOBDUJXb4Z3NXdi3lrqbc1KOUWTWyoLTcTZDxeuij3DklunZQHrWHDStVRaj4kf810w6jRwXACKJcAyxiAjShSUvVGn0zSEJuLq6fro0oZc8HdAniB0KrJMisEuAQvttSW45O,PmXExdUogQvEri4i9ZJxT62cggQb7xqgNt7FhCS8j6zXnA41yQOVEsFXtWlEyur6ReUfElbMSoxKaV5oQs7ZbStxxS9t9G5NH6rHU6c5PgLaXUdjTu5VjHUy6cVNrQiw7AeXSvZizdIf62hyZ4ejfbOZsI1m6Pfn5S4BS4HxEYwpuLnwgG4W33C3nPqyzVngANGUcJUBweVMl9cItw1jAj1KFqZyhIvF9Ku12r5idpUaCQpSBE06OAKBhxeQ1di2(lldb) ,I8WVboJncHXDXxN52WzpaTsgwuUZV1wE3CvPzery7wIG7PdAgpEhUSliHuc8bCEGVm93HHQqovABmSyiCxjjatmRna8YqRIwKT1m5WR1KQ52YAJv6ttgY1W00rFNeNtIqPSeO5rDXKgAGDJXS6MoaDiFS7YjjS4cWC7XGR2R0ItHHVEq2fCEfV56mD2SdHzv8XT95ah9mToH52TZVCjk77VXgt5BjiIVlbd6eSoqvwP4DcWY4oIQVM5Abjn47Q7Q,hWZv3DImnRFoNuNSJuaRknkPND3C2eJ0T4chHyY7HTl0RSeZuXeGYXy9SsQo1FKqGBRKfSqlx0kqkfo0tqiOWWh12ysuF4TZfA1DtCz2WqXFFZiLVylhMT6zahRq9xc0W8b1utYe6NQRaD6ayLbPeNZN5U4jxyEhORe7qweIQJD1RNi8zeHPKuELRUKRqrZsAaxeuJ6LqbGTSZ6eNg9MG4xnW89nAlnEHFpAo82EvxnUNLWQvoFqCaTk0IsYUwZG,pEAEDf3y2eHYBeQGas8oeFUQzjmRkiCnSPNUkfvWFHgqKLsYAsrDgrqfCGEVfhIn7TugDQN0Bvp852LPDQA8gZXg3iBjagJ9Fv0zAOT77xBJ22zsO9P7dTyh9F0vOxERru9nOZ2tD9lKpfDVnbPApgGX9uJ9Aq6QzknxqrgFacbSkzCuOayVJzM4YKfqzaaangHyinUSJpicXaWofIILdZ71Cf1wjpeH68uYWWB3nSuXHuDS4NSZwTRs7f6xlPdf(lldb) yHkVR1Z0ra1pxEwePljP34pk4fx5qNmeTfLRDU3jOpPgfQGQT04zRzlUJhmq00YjKlJax8D7PDx95sqIcdgFtMXMFDhNTNt7GfvCZZxFp4rGvxXzOosx0PHzBsPuh6uTea8hOHJZmxkAGRINDXpYJlTwUQHi9kwDYKcfhjsUGLuI0jfjq30qO5TP4Xs7DbLcShR5d9ZBLtmbG3Bomf7vEKN7ZstAAZYdceJWkWa8G4i3O1rrhKARhmC0kzmXWH1V,(lldb) ,5EbdjjONOOMdMWrjJJAwdTw67j4yKq6ygjjXCQuTPKyoq5wKwJtwCyuO3OAklLvuUtIXpXCxkzXEVDm2OxRf25DsuzBbQVO9WXfYNHmqpbeoMY40oLJiiLsHC2icTFC9yhGcoR5Nk8yz0L55Dbt1qrK1tMpCWWVNv0uVu22Toc8anTvx97zPxSssa0pBn4KmjN0CWhPMgMUNAf10TWcxRYQzZXZSZ6YDNFXCzrZDnsjtIJZPHiqw7DWaWvez7SEe,drequcqWMoJWHGcVDXk7VEvXRPk00BfMMMZhNcuKa6WMniEkdI2gbLHBuXeLqP8EhzQRoJitwk0f8ZNSFfDpsVLiB50A5vxu0m18NgH8NdHIUGMzEuZfXj2mK2IUG1dkkfDk7sYJj4HPZ9XrXD8OK53xUBP8Wp3Hkogfc7SwWucy0OLltKRv2iIXiVxJvvL4eMt0JgMaw5F8x7sjP9dmBF1wNMWHTymXnaSQTExyOh1K7oXntKU6cIsWrTpNOgSL,DaH7FW5inUhqXA8O0SlTRLrEboVuADCio9aMfXdDTu0GjyIQ6lCQQSLw03qztvricbmuUK1lldKncRYnloJ9cugo7RktZ8G01VCUNNqLuWnbOInpLd37j9lQgnNc9YkXTlqfhXW1w1QrJBslg4lyNOiAjKn2ywbnL7j0j3zUFZvjmpgEgdONKupPqpjLhW7mhOjNlu3Ya1zKBR1DyrTPY8aBwwf7EuoHao00xVL3MvpVmIfjPGDRpERAncIRJnkM,jynCSrUMRBNPEKGoC73gBw66Id4tqtQAknaddTrhKDa5D08hOsVNKxdevMNpdvaGRufm0z159PkopMN0oMIOUFAa6uIW2lRwkfizlNtkhs0RiiSBWCsvtJn87L7jrRtkZ5ciSCfczhKnnFt1ih2td8uvrrqrmrKvmy8w8pphag2KrOu3mkcfxuwEQouiVjym3WAzENnSJSEGUjQG7SAiO0hFP5DeRpwPjmNIPXsPf5dtkA5xS7VfrYCFCr5NnqlE(lldb) ,Jrsvqy4H903Jqdw7A4ZrDkAnTEPkggX8yE7kpNiaSOUhyNONW5zHe8tcGYvDzJP62iGQrUC7VerjX2jtf3f2knuVLa8zINeROsNiAIKZbxUq9Kq4WSbIpAIfp1nfW8mPSiLfF66UV32qgx4g50wogGimjlYqIeN3iofzncNWTvmd1DgsreIL03kiNdpsQ4WKCcDDL6zXLjGu2dHvfPep4hikYYZtCxCdKX9AurpGZXopAGS5kRyFTAquMtm2jUUW,jmG5n57vy6ntzzCGZIKkTKwu3IB0ZpepAX538mbwmic9rzOlo0PGXSfkn6wWVBr5I1Cm2WzgxAVx04gwSqUFGtIduulnP1pS96Ho8DWOXLwOf4VdYAADpL4uPVewtdg9GbffuGiUc34OTrjfCDUnXnnx63SfE347dnKhGsyFyqKCwIFnumBQzaH0bneM4KeWqcrQyK1E0djhx4dl1jN8rkmv2k57UEmVQLwpCWtClHEgMQ51ww1sTky8eX1dbrxc(lldb) ,6GSt4Ch17Pl24ei0JFOBYHj4RVHNzrdHHxALtzMo6rQerYIM1WCIMIGOjjZPLkE6sBspaDXWS7b3zwSwdmTSuDn36unukps3NepeEL6PF69QY4VwhB9Bot97qvof3oxXYd0XiCVn76Tbisk3ESB5RWBolUcJY1GzeFg7sSBA3DkxiuyMN2mI7J3o7lum3acCpkn5Aq4lIEGR120qNPgvCIutnMsKnNTj7KZrhgSnuszHT61RXLznDAdhQMDlYZFF,sSH2fbxOj18qkVWwexHlYvzOVR5W8hMsG7Il367R05w1A7NNnmfZkDPqRlpJwnab9JefcsMZsApKHpH6lEw7HIa1b2HqMakH2HTEvmwWlq7kaT48LOu19QJreAiXGRNEMI0dxDgew4lCu0VciRYDOoQ6HlSvU0l5XlmKo7DWNT0Ak7n7LA1xJw6v1RdVGEvQZvaCYGkstPqE6jSxbN5G2QiXf6gq1zldTyifByuOTVAsrNmJj8nqw34HGJ9dzkfp(lldb) ,BaqaoP3eL5gdW6jHLPplLeUiF4jn19cA4th1KMJn9BHrNPV28S8K5vjoFYKZ9qrHOqazleeIbURsdG37lFo5XsU005P6TYqswCUmj4dzM9rimcp9hFpWOuxjMcbiRlKHak9cfw09n9dFol90HTf4R0ViETgGNhkuoLDCBtVzVAjLNkJk0m3EFbS6yAbzQvi3w0JayyHz2NpuPi7JQf3YMXpFK3BZomjcvNV4iP5VuITHCzzOJtg14qfbibIOvRqt,EZOQ9jxnGI9tu0KjrD38v7R0rvCUAHfziAI6d3wJNmqO6TROti9IKxjzh2i1Xo5gHmT9UfTA8oLevbRix1hGnwc7ygjC8hufaZtveHMkV1cgQ2ms2PmFJ7izeUvzEnpCp0eTH9V3q0oOWS33SJoqScFarlMv1DGQ6NhormYNHvuT1wXrtN0n8io49sEzTfFRqBXHWcazw17ourPCDzvyoW2K7EE9tJFFVICBeUUXgc8pIWi49t8Od5kpnz5CiVxR(lldb) ,GOqd9PAcwqbBN6lYfLuoZL6Wv08widSWUd0k8JcWrYixGOcm2IoS9aQnTVBtpfQQihzpz0gyVY5v2i7tjqYqwbnz42210B90HpEwQ9eXv60GJQaEFtBcGfbjofFaLu0SA0ChmmUgpQb14XVp8vhApyvDuCeoajMXkwctP3YIhRQF1TUkfQ7vmDZYDyWJpd46IJvq2T8vRbHuc57CxXTDpwgIDWPM0DryU6UU5elXQ66q6RdRC5WMp7PEY9kHTzS3,Ax1cMrLayv4Gw9IJewUEzVSoDjea6c3kZ6gcHnPkvcbPBc4WC40dUBGOCSqJlUyaJkeVjNrpQsNzHifsN1sVEZnRkW1Pn6pk11VvLuWu072yvNZF0KTZ42tSmIfKK1jy2tRW0JSxwTQKaxd7HeTP74JEQe5inHJQzMD6PwfviWxiHfb6wn30szVtrl0QHxT8Mo5thmQczP17wUj4DpGn6djPUoqMDblvfa8gJqhVPElH4GOjc8zcNGSTut1S8RlC(lldb) ,qoaYFmbbAcY2aHl2BzcKGJXBpz0NWzXVq6CrTfI7zuJIIBQ7DBMAaHE5583cOvvWlY9GqVckFPtbLOYs9sVvKiRxCsNBMna2FupZvxNWimTrkOd0O4x972gfeehMk2RoeIorioVQtH8BSMgW9FJYHVpnHf4P6fFkkiGNKUqwVj6tDuY791gNwqoUMv0LE20mTzataFjyoheklUZTZZKO6Bn2eLgTnIF4csfaSY7TjR8G1SBiGGWiRX1TM8oGVjw2,iziUjHtK2heHLAXUXkeew2vgT17lM3lDRM7S3080Wx3VEXTWbOjHFwgMXUWA9M6lIITuPGKr6colk9xue5YBsmiMopvODurPlH3nAYvJ77u5vV6fD98as9F4mjgpczqLtFwdigO6dOMnUgxhayZ9HpcsSX6dGknTvxxp3AkkLnlfhVsMuHohgQdILcsfp3ZXtILtp6NiA83IU2Uy3SgaHC2p2xIgYTrZ8MuM65suX3Lw71IzmDQOF7LUsr3qd8Mz(lldb) ,KSjoPIrzDo8ch8EwJPQdIUlZmcMMdkkdWNT1a0LHQkiteOetjKzQNhnAI058N8svGu6rC25k5QvthsOpKWQGnVgx0rmSlNGNsoyYtyhllM30uvb08WYIf5Mp454iw0xMlLKPcp5mU1qmOqCX9zJXbfJMspePtDcLAxrgtk4VVP2BRTdtmDRaL3FLYwAKC1bwYmhUUHWHixsbbnFTRdKdCEHphbfcfnreLPLFPASeyZoLTjojCDemNr6z83Msl4om,i4KnlLA4bieGzNKm1pdp2fFEu00m81J9DyZnBP800YZBqB1GydNv1pPO6tq9wgJbBD0kTc2FWwlcrlqWEjRAKEDXQ0Dz4qR6CPHnVPS9PJHqtY6VW2Xu6u2tOHLl6TjgB47xyaPkhukikcAVA9LEcbIuyK2fsm7U3FKMEZR6VrnTZm2xs3R3SClvEuhhoBkc5305mSkdbfCm3atW37Rve28nOdSk0y9pBuJiHJpygWjBBqCZMiLBKijC1KzKkSjw(lldb) ,o3A15xx4xgU0eKO3XOZJVrtHRBlFPYIkywbPDqdQBjQIlrwmDZ8UDXtM0WwA96yxdCpC24zhOFue6yR8u1RVAZDJol7x0UEcMc1NTzRxhdYdrBHUediaoi6xYhH8N7uhUBLMLWjyn3TNNMihZRN800P3faTbn20kElRcYfWq7kBVNNX578C9yuYHdf7bjEeZSVUuyss0BVd91Sggycyhht3Bm08UraiE7NCuKWdUSPKk115JhlHxa2T6VYgUUHRO,6OnFASEPU4xbv5eIemJ7firaxT7f8VYA9caJQNOoa6UGqCvfXr6XnbRIkB5lTieDAhmnoKJ2VU53EVnAqm5IJNoayPbkLufjUeiAtBA5m1qwNMvReoHOqvxY9UcLZEjJut8I6z9Wf0emPMpfLKl7GWq2rhENEiMhw8FFcBUJnfspfarGBy4cOqwAr2RQoSfzw1KOyQpxQ3KeUwNBRlu9QBzDh8YXyiky3HUKn3Mo9dKbWmDF0K7KDyQIlQJqM5IL(lldb) ,lvPCzf334haeQJ51mwX9GazrlHt56QdSvf1mwjH3eKHwZpvXP54ugpNjHhGpbpmWhKe4vP9V8PNLeO9Ldj0t7juD0btGw9iuhd8vtgccoq9dsCLXURVqpRbUxoeyVRdcNcpZ5pjfI0qr7U6HlECI2z68i8X4edFqVlNPSihbOIrMxY1aG2CXaKvikSXpKOOsLMzKsQ9yK7KmSEI6fGXRg7ncfBz1opEhHQA57ArLSjai9JyJ81uwlM7fnEslT0KS,3TRi1EyVyK3xbIJ49lbl4XB5XsLXgWKRkQy1HOdFrZnOeEwSpx4fVGLKsRq9lcgTQD1yVc8TNOU46MZ5WLiL97GfXIzUsd0cMe7w0WYpfTgr2KIgp7cHy93rILzwpmvOhFUUXXE6ky9uuo1xgGt4ucu1MeDGG8HxSO7Aro2J02q3TjzjEyq1igIHxRTw5FJqCO0alXXrqS8yvW9xynSPHrH3XUHtEGRbBUUxfPb2cGPLLbnqnoC9avKGj9R4vrKv(lldb) ,Z4vMGsEoeLjYmdRWbrz3lNYxY1k1B02d2lf5m1q41MOWpI16g7l0dR0Ed7ecVZtHcUtyQM0vEwb5y39kGK2jWgbLdRyMSwYfS7iq7qpFOCEj4oW681gPdyxvOyJkXWYjUM5SfSw9iRUzoqK2kQVxQVmXFNZPn3pzf22ts5R8xq3tYRw98ys1pLptLV2mEFfRhNlyehMF94eTUMTor9BUA3Iy6yspS3iVKPvCsgbRa8CambKCbkAtFjOAIfgeTAWF,OuuVCi5A91zcsGtv7u5SxCFkpkmw8tsQxdLYjiNRIFhZCI42PMzhzDvXC7dbJ9wsTeYlwZYzo1WQMLArZVuwFs5LaQ2J9599BGUpUYBdGa70bU4a1ESXG0wfx4cWtXQASQzz6yi9vsXvBAbFSO2G8Y56iVEt0ieOLw0wucirl1vQkvMVm8AohWp0an6EqzPZvMJnDYSaXaKaQQr9gmvvuRj92byVI7B5qZ2tG45kQENchgxLBd6O5s2l9qzeFdDw,Ga2a0eI8zKvQBHgGiEZYufvTOiblxD5fx5dZBM1jJnIfjMh7sjnLNB83V3MJzuLczlXJq4mtBtX3kL1I5TbnyEiMgl4pIldUV5iYd8KuAR3QDvz95zn7RhFFwgcIFVfOEec3Oj6Bepq2C4vRL1wtBqZrNOSpykxIhCxAUJzk230jf8MZGyiKOq07eA4h4Vxc8knbZb80zHodHeL09gQPVoaTonqGC5UCLb6k1n34Ekts6x9Wvv9Nzmr1W6SOe9ss(lldb) ,66qXTYdw0RyHy9cP8pkYf7ptB8XbPT8Ky1ZjRg5VCMz9UEq0L9lRkj24wwVYSfCf88kGWKObRSUlSsJWvtWpSUZcfImPDbP2jDtp1aLnnXBjDpkZPNqnMLePEGTpzSFid35RYzcx176CIrEppIbUatDJe0JiSLKknV2ztadOJ0GXIqpHLzGJh1MzIcpfi9mTTYOjeBqSyEOF5Kdzmkx5BZzxpFxmqdTPpQjpM187z4PhsFRUKeDP1aViHu1d0Czu,u5E7O8qnVVhLB9CYwATb9Hho17D7NseN3iRraGDDTJcY9f6R91v7dZSwZzJDbIZizLE0FHJIzRIgAScLevOq8QSkrB8oP9D9RZYbkLaL8CAuHunV56yMWlrRAKSlea3GWyK9yK2kSnEOqcsRzeNcdDtal4nJqIW8oiR3TQvXo9q6RKrGFZnmbLOtd3kDHU9PKzwI6P7yrhJYTZuLKwX1f3NX8RacOLddPewrBxAjNoNXtBcdO6WtJjzXNkYaZ0G8(lldb) ,9GBHAm2lMfvm53MoMDM4mocaaCVIYwqYCDopDHuGsDoWQUkI2RWVT42cDJcBpuYyUwTINhmdnkiFnZ5eaTpK8jvn24NPReYdLrG5UsB6W3Re5saIzB17eKvZcz2WMmoclKn27kaebPC1n5sk8OqcrCjb58N0lcd6oUfetO4xvGyzGMdpkJ59WAeKO9HC7E6EwLWqVJpf7YPF6deWr2goZQAuczyTLMMyAqASKDTQQ4Ke24NOUsJJieSuUBP8YtKYHjaTqB72aBWYEzwsVkXJB8PiMbmtg50k7sIdRfrcECQlNN2YRlkg8vmApNxtbzbW0czZdNz2m3tS3zVbbwmIPuLkTGWsWWupL4Ith6zXec6GY5aoWMJu4JVf6KSroDN0Pkcg7F41yrhIFvFjsPzj1c37MPdovy2MHixDkzcRpZhCECJEzKMC9AitFarGndzDLFFWqLd9WeWY30R3lC2z6Z4L0Kb4KbzvwjZM6xIAGSb63EdoCFvjpKpDMAw3RP7k,OLERY6tFt0Q4JK55gIo1XQ5er9s3SfzjCFCNk3DHbDjvOUhBZewhMmOQnGnufxKknZeCJhbU97p82osNx7W5IZVJF57PO7FD6669HVeBgyqQhQwdXl3TX9lTMWJPWT4ixZ3g1jhaRyIxl8XcYuxHwoo7TBTLhdIb2ia2HErLmvJu6i6YZZTBCHp6TLeV1PDKs6QOjzrFhYYBpJ2GPO0I67YcfPgQq0YzKRBsznn6mAFQmLfRA50tGlBW4Prwj7ET(lldb) ,6Kq6XVZOb9lfloBc7hyO22JjsFfdxYANrtSgraR9wTfKTbUZGMLzsqCe2BZdjdddYPa5YwLcNdhh4F4Q1GCLxfxAc2OUOQwuVSPm9ojWi8Xr6UEbch9D3NuztU1rLey5aWzg80MTp831hnzeD6ArLcMcqBsOTJQCyOv04BwWvNY6uFQP4rdZSGxF0NuyF4yFEYJQRSwB3BXskTxIqDP3kYzo85LSo1zd9rkdsidVVTJyq7Pwd23HIVg422lynGkg,8gRnGqh6cTvW2j4StmOJJFCnyT34EogN6GSwljmuV8ezVjfuWowv5fHO3bD9MHOKPnK6OfbRgCuRXKpIJLf9wCDDQYxS0t2dsf2pUX5l9rdEqTDTAgMZALQeQ2cSuaMRKGuzxJeFCt7qFn3wK7HgoNEvRBBS59oscEOVAjlDqNxkmdrO33Ze614gkOe387rQAiC2JX4aJcLicBQcwa0PR5t7oZrtejWcdytQ92ameGZO3o22ZKNQsNog43fcmpIi(lldb) ,lodXk3LfOxOduDzdaodJ2EyROmEjprh0pkD780tjKNC7kP0e9RkPTOGITd9nWz0E2RUzZ7k8pITbC1eF4IF5ZfNC67q2oI4CPoaJuZGEhHLF1lhdmrjuu6rywE92LLJAx58tII0hBxcw772wcdr8qdRGJQ0SkqA52i1ImPUNqWgv6HM9sqJZxlriMIZeCf2hiBBpV8ZVIN03Ea0hKFctxupDLmULXgcboCrCN89ELqFW9eihBx5PMYJ3tlXwwLaT,8yvEJayHxDJKhuhrtAcr4aLjEY7pwvuSXOP2g6WdV7nuS569V6FdJEA1OBGvHbmu2QSciN4sTvdlOCxYXxzoeUS2DtRcj5F7eGzwTlf6FydqbMhwgdVwjDWKSkpNiOp1WNm5xVcW1W7UwQBvL37DTkdmQoDA95UGDQyP3CKPWJoOFTTBnHz4B7lsj0T01XhFhLbFtL9PbPDz7KL2siPfibUGO8jQQP3T9duORkuq80SADEvdniut5cqQ4fluh9Ob(lldb) ,ox7bKkfW7p8xhWw7WdYB9vUgIp31qyOqwc1hBx6JE0QcV9uWLvJWtQgxn94VDeTXloEHP6gWVF8mVD0UJYl2LKA4AOQLSWaJmFQS4QT2d68vTDaDVPXcKJiYGMGaxfMPMf3xOXa1epD2NOOLF3IZ5TLTG5e2GUhmGnzzD8xpnPBL6BanIr7V2HVG2YfWmz8hvGE6nkaBVIuuBf3vTLkqT7AiHjPK75oIwGpES94qekyNPWIZ257Fp32lOskyUI1u,rm15hM52M2HIUW2wINOR8Wua0QLCv8C0n4hxOtAJjcnqjH56yAe7jHOk0njUroH1NzmE1bBcvk6cf3iBi0JXBH7gTwKohxsd7T3yyhqg1MiiEQ3k1DXbOuoGQlaIjnAoGQrdARgh2NeydahFEXeqRtLUkAf8dNJlgBNzh45LjpmocIggjgAv8z0PypPkA6HFDq030FEnuChLJblzKIs8Edlz7emKMbcHXVojBlNxAOqc6xCPSVC6cf58TheSSAIm(lldb) ,19w4gwELBU7qmdQ8s7HR1NcaN4unRYrimDGqroHPUL6crXiS2aiCh4vTwGzegujNjeRtqR7M7yEdTMCuaPzpQjd1T7gTiiUpgQyLBJ21zwGbmePBXJlvNuJbZQBhZrfci8NcMSEvMdDEpmvw6V8u2RdBBLWJv8ZMnmdkWmv7d5zo7sHfXgmnqkxZT2RLZme5QrWefMXILypknxiP7tlXcGkLWMfkS4m0Ezv4Qb2LkuGjElW4n08H3SVC8bWGyaMZ,0YtVtD6qkquBs44lV9Sngrlm9a1tGSO95KxDD6gEZ6scdDLgKOojPjoQfdPrhyePIIoJoNiJMx5K2XV74XdxHICahlGAdbLwBuQXRBkVdqGcm4MDNbMrt8D8otwZKFt7he72gBivADighviXi5DAT2B8unfM5fjeqeooyvocBrggPyVI7fqfgNHjGoowPLjSE5APzaUSgLZgIbdhImv2vINV1fU33fNZzSXtWe2KooWGKkweSiewXalty1dnE9ZL(lldb) ,D4cSdAsD8KNdeMO6XpoO2lnAp4RBPPyfR62BnMDEci3KyrHLZt3KJ8rGro5m5HC217NAMyZUsRZBu9WeoVTO81QYxg0wljx3bqDMHtCgNWvoUZBB5AT6GNYMWhnnnd54KKnaCrUvjA30Td2S0wid6OXWGtFMJ3nowRivld9RsoP6fDPGBePfQCRZtw3hL25FRmDgCFw0ILW0nf5pXR58IXtHqNoszd1ogLtbL3Z5MStEQ4qAn2pTSDlslQRBkGyy,wgtb45Twl15EIg6wPOQMXuOjNMqlNOzbFr4WI17TIDRYrb6ifVfE6zGMNzTo9OBC8MEYgBH6hbh8mbpPXDeqT9bsOX6MhPDQy67yLchDzInuEjfsEgAKWt1yk58QVyPvPzPO0H2WjzqKf5D8qZX7tCsy6IF40eHIIdfrerFYbzmpYfxrsXOi8e8pl8m5K5KqHm3qbZxKrqKz7wLalc5EQtG0t8ueZ3Yfumbg37ultqQsCSA3yyC1LDeT3fH8gHsA(lldb) ,34KDfBXJDXWRCxJx9TSuWTdWrG0mBbmhNWmZJn6jWNZ8AauDmQGYvdnRs3jY7DXbsM4rjV7YXqiDEnU7QkEat1fL5wyTnyT79fAAtiCNR2uFrWIySRpUzl9GISrsreWiiWVpLcA2wnrzJ6c8YgroW9jkmcHoGDKQG4Qli1lvdv7gwzhcMAtv4iQB8hyMukckoDQzppxZag034ccXNFXOSSggXgRjKF9S3wPnTV4stxBlpIiA2PCp2NaSI8IP3l7y,cjGdGbeUCB4Woot3s1ZqKI5lksnMgOC0yUwXj6kXn6xpwPuYkxHBQQPJd6CF8AjtPlhj2FvUe5jj5oc0aEIwuJc4yhqnnygvLmzjQaGGWlVQVbGCL8iqZoXftWUgtSvSuVxBw9qZECWkDB7EkXaNpk10yAHIaf0glpsanPupapiVcZiGhHNV7klHDSgW5WR5oIRCeXqYuClCZHDf9rEHojFjuvu6xZKhNfJNFCwYBELYgveAOb7l53W71s3Iyqat(lldb) ,rw9iVIdt6OSGEle2KegOKz3nAgXY5umWvznvOFCUEVUv3lZe9UMuNRCYfOU980y7MOzoQHtSk3LB1BGrx5Tmr5Xo9cXc9TsnZZvDlK40rLmEoTFJ931I1V2VqCv4My2oKEaJfkG77MYnEDn6chskJ7rk8fEUldhaldDl1oxzCTXdHnn9xm0iw2BnlS5f5keIopMYwGrTY2xckzCPsiBKH3KyIIjZD1HUKkw8SIXTjR5AipNn3BPGCnVy473zC9VB,rVbQ0pfASBtf87B2ZtrQO4jCyL6yP59CMMFEeaPW2k1TgFnKSHFywsFMqhks5o5gqgLVErhgUkduNTEe9X8dLzVWeiaIoq2nZygbZwqCAX2FleJgr5e68jv5kWENLgGGayVoQyhHohDYQ6QwA5yWL4pPQzIZluEFRp5UP2eLvLMtZTPYwk4WWqV1il84cyAYtAxz9OnxlMfBL9AxajZvnlOtj3cBkD1d8RCTg4z6T4LjULpXZuDfcpsxTeQWvXBq(lldb) ,e8SqSkoawdG2tlUQnIslMvOV42eLIRvRlHo3s5jZvEyDa5mNsnogzO9T2tFPbOySTKtHR9ugiUT4MZLzJYrPe94KWhNtkp0aExZovpy9X530LFO4YFmvidblij5GpGrZpUObjjrKJn0OK2gKteVXbybrbirm3IgbkcgxpBv7JSh3sJk9tZnQVGty4OFWRrFztC7IzzANFlu7lAH817tjzJuQEZxFbchKTb3JHwiDY5J4CNdcU0353BKImvosScko,6r3J4G9LHydFjx0lj7SIgLUknkTSYGU4e21bSd0DysKBGSfOeXt7s1Fq2f86BO4KdJTuJdxRRlDbRVcTvS8SjqdInkZyXuSBeATBnkjZ3f4gKLHds4CZohNPo7R8L9flCY9S7mJj0SJkWGrjco9e5Tqh9i7Sr1RqAPHw3jqZw1RqsSanZMmPZ1iAHX2NlDHkGOs33a9kET9p1ioWs6BXVb4NMIQg62eU1cfjdUqIaBKQdbvxM3Vj6SzKRkETz3F1,84xSC72rKFolJMVr9t9BO2qyrk7ARkp0OhnNRrEPnLbWhUIAtK40QUP48TEYRXo5xBPfsn5p7DEcHDCP8F4xP7oAQXc0fLa1W3uxNlh3pW3lqzwJig4wXdEDmJQWjZOh3rmOzr1iuXOyj3liyBwnxZfmcDk4yFlTANvjId46o9mzGp416x8dWjjZeDAbOqtSkdACKF8TavVklO7hF1FFzJD1k6Xu0RMTkedN22P4hirAin96ERkJVt0tyAYwIDIp(lldb) ,T57EWtQIGUA0mez2Kmlk2ywwTuEMl89bbOpRPQWsYqGCE8cFt8ubWn0RaNe10s5IfCruRn79gfZAkIbtu5AzZCrrqbcLzvJGUv3nYH4RQuUdnpTOHEi6zoOcgTxe7GKjP7ZiX4hY48pAw19xSmN280bzH3lcJOX0nzh1iVSqAWkeUTHYpw1gtSwW0aKgAyFxSTxr8FITQm31k42jnSA3j9jaetyB1qwC5AF4j2mEh88ceppNf2qqAhWGVFCdFYwg,rPikcLttEUVT5agk6lVpwVrnhW5RQTvSrSDL75FaCYm0M0R5kL9l1vG9xTrw8isNwUkWx5fLn0WrNcQxQgoZs7nscW8nScNO53lSgRED1dvF3Zt46sPNuSvdaKH9CR1EPQ8MHLXzO8IMY3rDtRXyYofyEIPSv07BeJnYUMjy7BmIkZPEYxMXydle1JMymhLecO5QhLMKxM9XOci5SK9kPRvGb3354caTyedVkwxXYtm4FUPXiXA4FasiHHVOrZDV(lldb) ,Lqmp77uc9jIWgi6DHPHxAXjXJZYtpaRavK8prsflDhFyOvPPXYVnNZkU69A1aGUYLlT89YDKgAycmq00Psz6YdIOYERh6M1ExOKEzWxH2m4ZiTDBRol1Y3WBucOc7PWoMqalN4Wou0TC1aXUpp9KbJLIVslkyh1plTWFqSZzoNL6q4PchyjDLy9T1nDKzSVtLKTRpidKfihYTelJnKuw63jPj4GwamDKWGHx0HydhgQd2NjntHBN8yOt04ZBi96U,RvXeB9sk5GzYN0S1rAyWZ2hpdnLmifWg1QhwR1celaRx4pZoN4eD2OSUMvIxOtVgSKIjMn3tQ3aJUYEtrd2QekRsxH6FcdCMDMZnLKJ4phHDBHfWMNkREAR3EIQ2dMVBT83t2fPWITR8GHlk6pRmvfcCfUfP3A13hYxGqlU6hTXNippKc1l2DzUmpPf9YiB7vVyUZKlZbqfEEM9sd9IALznXwoGExv2AZQvt1DQtRKdvhvgNDeJkWMdNbzFr23Ie(lldb) ,NSnjwWVVL6kfiEkbd8dJiVYp1Sisd5Sd4WtB6YrpRXUbJfPgo4QcWQxZv8g6WNv5jGnsiSYLzFd6bx7r4WnpMBExdHHClFhcZzSNCN2E2pUDuWUdFbjDkS6YhwzSx8vO5EBMfwL940aSCRoT6MdzOv6lLkHtpHo4Wk91qiPBSdlUx0hYtG9brvmrBbH9GgiaB3zy93ironTKnrWIEJExzDhm25jBoz1akmcAQtPTWK5cVJ0n8bWeCvPQC3bSrL1d,umjv5qYq9kTQjEiKtXlFupixPJmaqe5RWUKa1IfIJMutyDJPaWpHB3p9sbebb3SzG0UxwMETyVgaMqAwMxcbDY5z3DZbvB7fjoCu8pOmUHtKlyUEktmIdmlz2XPrdSKA6iOq3JpjZiCzWpVw11iBruTSr36c5hIhxns98bHfStLMUJS64M3katHDQWxquWPBhXhm3OlfdLiRCfM9I0hdOFk8S0iXqJsqZGkVgS7J9vBrNHvu0ogenbVclXEShzHR(lldb) ,0qGRrrW9IIZ76M4hgdSZoteO72A8VQy9a8gHxhSgYFY9y1GbKppHEoxHSuxShzvgvIMsfPwkld4mJmUawhzah6mj5DTApZiTvaBA1NzHXK7v5PI0hbia2U7z4V0GZfnU5qy3s5Xmzy6Bqul8aCI66nj5pbEY2PdQWQTEZetmETX0mD3sQosmFtbl1XfRq2hK3mboPXOxEuTPB8AIKIN3tnn7h34vMJ7Ce400DIwgEWrYVVHUtS7eb1vKrqZpmAreWBOyYz7'
    actual:
      ''
  ...
,2017-06-01 14:38:27 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-06-01 14:38:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-486(lldb) ,5-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:38:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:38:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-486(lldb) ,5-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:38:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:38:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-486(lldb) ,5-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:38:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:38:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-486(lldb) ,5-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:38:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:39:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-486(lldb) ,5-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:39:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:39:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-486(lldb) ,5-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:39:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/69A187A2-B216-4865-A7CB-6D53DD8E2497/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:39:50 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-01 14:39:50 - DEBUG CoordinatedClient: 'test client failed'
2017-06-01 14:39:50 - ERROR CoordinatedClient: 'reconnect_er(lldb) ,ror error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-01 14:39:50 - DEBUG CoordinatedClient: 'test client failed'
(lldb) ,2017-06-01 14:39:50 - DEBUG CoordinatedClient: '20000'
2017-06-01 14:39:50 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-06-01 14:39:50 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
```
