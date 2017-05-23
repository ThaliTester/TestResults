#### Test 1219585698171119_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1219585698171119/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/AA55DCA2-5870-4DE9-9107-0FEE8764A8E9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/AA55DCA2-5870-4DE9-9107-0FEE8764A8E9/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1219585698171119/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1219585698171119/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59104"
,(lldb)     command script import "/tmp/AA55DCA2-5870-4DE9-9107-0FEE8764A8E9/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
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
,Platform ios
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-05-23 11:31:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-23 11:31:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-23 11:31:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:31:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-23 11:31:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:31:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:31:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
(lldb) ,AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
,AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
(lldb) ,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,Optional(false)
Optional(true)
,AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
(lldb) ,AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-05-23 11:31:43 - DEBUG UnitTest_app: 'Running unit tests'
(lldb) ,*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.554046869277954
(lldb) ,2017-05-23 11:31:44 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
,2017-05-23 11:31:44 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-05-23 11:31:46 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-23 11:31:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-23 11:31:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-23 11:31:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-23 11:31:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-23 11:31:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-23 11:31:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-23 11:31:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-23 11:31:46 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-05-23 11:31:47 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-05-23 11:31:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-05-23 11:31:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-05-23 11:31:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-05-23 11:31:48 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
(lldb) ,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
(lldb) ,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
(lldb) ,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
(lldb) ,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-05-23 11:31:49 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-05-23 11:31:49 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
(lldb) ,2017-05-23 11:31:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5720FF82-E531-49C,E-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-23 11:31:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5720FF82-E531-49C,E-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-23 11:31:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-23 11:31:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5720FF82-E531-49C(lldb) ,E-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-23 11:31:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-23 11:32:04 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-05-23 11:32:04 - DEBUG CoordinatedClient: 'connected to the test server'
(lldb) ,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-05-23 11:32:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
,2017-05-23 11:32:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-05-23 11:32:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-05-23 11:32:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-05-23 11:32:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-05-23 11:32:18 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-05-23 11:32:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
(lldb) ,# teardown
,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-05-23 11:32:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
,ok 4 should be equal
ok 5 should be equal
(lldb) ,ok 6 should be equal
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
(lldb) ,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
,ok 11 should be equal
(lldb) ,ok 12 should be equal
,ok 13 should be equal
(lldb) ,ok 14 should be equal
,# teardown
(lldb) ,# setup
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
,# teardown
(lldb) ,# setup
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
,ok 31 fourth
(lldb) ,ok 32 fourth
ok 33 second
ok 34 secondPromise - in then
,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
(lldb) ,# teardown
,# setup
(lldb) ,# queues handled independently
(lldb) ,ok 40 all short operations completed before the long resolves
# teardown
,# setup
(lldb) ,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
(lldb) ,ok 42 executors is called
,# teardown
(lldb) ,# setup
(lldb) ,# exceptions in the executor are properly handled
,ok 43 got expected error
(lldb) ,# teardown
,# setup
,# basic
(lldb) ,ok 44 sane
,# teardown
(lldb) ,# setup
,# another
(lldb) ,ok 45 sane
,# teardown
(lldb) ,# setup
,# test sinon sansbox spy
(lldb) ,2017-05-23 11:32:49 - DEBUG testTests: 'test spy method for global sinon sansbox'
(lldb) ,ok 46 test sandbox spy works correctly
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox stub
,ok 47 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub override
,ok 48 test sandbox stub works correctly
,# teardown
(lldb) ,# setup
,# test sinon sansbox mock
(lldb) ,# teardown
,# setup
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
,ok 57 correctly parses USN string
(lldb) ,ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
(lldb) ,ok 60 throws if usn has invalid generation
,ok 61 correctly stringifies peer
(lldb) ,# teardown
,# setup
(lldb) ,# onPeerLost calls jxcore
(lldb) ,2017-05-23 11:33:13 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-05-23 11:33:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-23 11:33:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-23 11:33:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-23 11:33:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-23 11:33:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-23 11:33:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:33:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:33:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# onPeerDiscovered calls jxcore
,2017-05-23 11:33:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
,2017-05-23 11:33:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-23 11:33:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-23 11:33:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-23 11:33:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-23 11:33:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-23 11:33:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:33:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 11:33:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-05-23 11:33:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-23 11:33:24 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-23 11:33:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
2017-05-23 11:33:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23(lldb) , 11:33:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-05-23 11:33:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-23 11:33:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:33:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:33:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-05-23 11:33:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-23 11:33:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-23 11:33:29 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:33:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-23 11:33:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-23 11:33:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-23 11:33:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 11:33:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-05-23 11:33:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-23 11:33:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-23 11:33:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
2017-05-23 11:33:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-23 (lldb) ,11:33:46 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
(lldb) ,2017-05-23 11:33:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:33:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:33:48 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ,e'
2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-23 11:33:48 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 11:33:48 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-05-23 11:34:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-23 11:34:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 70 Can call stopListeningForAdvertisements without error
(lldb) ,2017-05-23 11:34:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-05-23 11:34:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 71 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-23 11:34:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardow,n
2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-23 11:34:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-05-23 11:34:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-05-23 11:34:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-23 11:34:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
2017-05-23 11:34:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05(lldb) ,-23 11:34:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-05-23 11:35:49 - INFO(lldb) , CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call (lldb) ,of onCheckpointReached handler on a single db change'
2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-05-23 11:35:49 - INFO CoordinatedClient: '***T,EST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler (lldb) ,on multiple db changes that are out of the checkpoints plugin delay interval'
2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: pas(lldb) ,s,ed - test defaultAdapter'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
,(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
(lldb) ,2017-05-23 11:35:49 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Can call start/stopUpdateAdvertisingAndListening, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A1,04-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/bluebird/js/(lldb) ,release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-05-23 11:35:49 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
(lldb) ,2017-05-23 11:36:46 - DEBUG CoordinatedClient: 'all tests completed'
(lldb) ,2017-05-23 11:37:02 - DEBUG CoordinatedClient: 'test client disconnected'
2017-05-23 11:37:02 - DEBUG CoordinatedClient: 'test client failed'
2017-05-23 11:37:02 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, (lldb) ,event: 'teardown_Can call start/stopUpdateAdvertisingAndListening_finished', test: 'Can call start/stopUpdateAdvertisingAndListening'', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000D,DA9D4BE0/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:291:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototy(lldb) ,pe.onevent@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-,A(lldb) ,104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:1,2
Emitter.prototype.emit@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-05-23 11:37:02 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_(lldb) ,ON_EXIT_FAILED]****'
,2017-05-23 11:37:02 - ERROR runTests: 'TimeoutError: timeout exceeded, event: 'teardown_Can call start/stopUpdateAdvertisingAndListening_finished', test: 'Can call start/stopUpdateAdvertisingAndListening'
CoordinatedClient.prototype._customError@/private/(lldb) ,var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:291:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore,/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/(lldb) ,private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/Tha,l(lldb) ,iTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/5720FF82-E531-49CE-A104-000DDA9D4BE0/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7'

```
