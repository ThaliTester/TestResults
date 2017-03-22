#### Test 112016147cd7538d_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/112016147cd7538d/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/31B172AB-0EDF-4837-968B-C860032AB75A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/31B172AB-0EDF-4837-968B-C860032AB75A/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/112016147cd7538d/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/112016147cd7538d/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52767"
,(lldb)     command script import "/tmp/31B172AB-0EDF-4837-968B-C860032AB75A/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
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
,2017-03-22 14:33:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-22 14:33:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-22 14:33:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-22 14:33:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-03-22 14:33:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-22 14:33:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-22 14:33:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
(lldb) ,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
,AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
(lldb) ,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,Optional(false)
Optional(true)
(lldb) ,AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
(lldb) ,AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-03-22 14:33:07 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
(lldb) ,Number of passed tests:  13
Number of failed tests:  0
,Number of ignored tests:  0
(lldb) ,Total duration:  1.354096949100494
,2017-03-22 14:33:07 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
(lldb) ,2017-03-22 14:33:07 - WARN testUtils: 'myNameCallback not set!'
,2017-03-22 14:33:09 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-22 14:33:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-22 14:33:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-03-22 14:33:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-22 14:33:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-22 14:33:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-22 14:33:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-22 14:33:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-22 14:33:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-22 14:33:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-22 14:33:13 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
(lldb) ,appEnteredForeground wasn't registered
,2017-03-22 14:33:13 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
(lldb) ,2017-03-22 14:33:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-471,6-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:33:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-471(lldb) ,6-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:33:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:33:18 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-471(lldb) ,6-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:33:18 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:33:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-471(lldb) ,6-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:33:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:33:37 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-03-22 14:33:38 - DEBUG CoordinatedClient: 'connected to the test server'
,2017-03-22 14:35:03 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-03-22 14:35:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:35:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:35:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:35:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:35:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:35:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:35:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:35:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:36:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:36:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:36:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:36:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:36:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:36:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:37:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:37:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:37:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:37:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:37:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:37:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:37:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:37:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:38:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:38:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:38:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:38:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:38:52 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:38:52 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:39:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:39:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:39:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:39:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,bsocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS(lldb) ,.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Ap,plication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modul(lldb) ,es/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:39:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:39:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:40:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:40:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:40:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:40:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:40:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:41:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:41:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:41:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:41:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:41:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:41:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:42:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:42:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:42:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:42:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:42:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:42:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:43:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:43:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:43:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:43:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:43:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:44:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:44:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:44:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:44:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:44:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:44:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:45:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:45:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:45:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:45:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:45:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:45:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:46:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:46:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:46:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:46:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:46:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:47:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:47:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:47:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:47:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:47:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:47:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:48:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:48:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:48:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:48:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:48:42 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:48:42 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:49:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716,(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:49:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:49:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:49:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:49:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:50:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:50:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:50:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m(lldb) ,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:50:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:50:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:50:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:51:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:51:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:51:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:51:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:51:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:52:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:52:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:52:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:52:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-22 14:52:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:52:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we(lldb) ,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:53:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:53:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.(lldb) ,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module(lldb) ,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-22 14:53:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716(lldb) ,-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_m,odules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/co(lldb) ,ntainers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-22 14:53:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: we,b(lldb) ,socket error', description: 'Error: connect ENETUNREACH', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.,prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/App(lldb) ,lication/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6929FE7B-6488-4716-A956-A9C4FD8C880E/ThaliTest.app/www/jxcore/node_module,s/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) 
```
