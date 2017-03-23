#### Test 111727539a32d624_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/111727539a32d624/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/0291B2A3-EE27-4DE1-89AE-CD58067E7A12/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/0291B2A3-EE27-4DE1-89AE-CD58067E7A12/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/111727539a32d624/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/111727539a32d624/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57124"
,(lldb)     command script import "/tmp/0291B2A3-EE27-4DE1-89AE-CD58067E7A12/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
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
,JXcore engine is started
(lldb) ,2017-03-23 10:39:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-23 10:39:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:39:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:39:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:39:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:39:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:39:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
,AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
(lldb) ,AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-03-23 10:39:09 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.307188034057617
,2017-03-23 10:39:09 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
(lldb) ,2017-03-23 10:39:09 - WARN testUtils: 'myNameCallback not set!'
,2017-03-23 10:39:11 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-23 10:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-23 10:39:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
(lldb) ,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
(lldb) ,2017-03-23 10:39:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
(lldb) ,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
(lldb) ,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
(lldb) ,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
(lldb) ,2017-03-23 10:39:13 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
(lldb) ,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
(lldb) ,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-23 10:39:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-23 10:39:15 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-23 10:39:15 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
,appEnteredForeground wasn't registered
(lldb) ,2017-03-23 10:39:15 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-03-23 10:39:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B2F57F5A-6519-465(lldb) 6-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:39:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B2F57F5A-6519-465(lldb) ,6-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:39:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:39:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B2F57F5A-6519-465(lldb) ,6-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:39:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/B2F57F5A-6519-4656-AE11-80AEC56406AC/ThaliTest.app/www/jxcore/node_modu,(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:39:27 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-03-23 10:39:27 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-03-23 10:39:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
(lldb) ,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-03-23 10:39:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-03-23 10:40:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
(lldb) ,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-03-23 10:40:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-03-23 10:40:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-03-23 10:40:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-03-23 10:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-03-23 10:40:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
(lldb) ,ok 8 should be equal
,ok 9 should be equal
(lldb) ,ok 10 should be equal
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
,# enqueueAtTop and run backwards
(lldb) ,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
,# teardown
(lldb) ,# setup
(lldb) ,# mix enqueue and enqueueAtTop
(lldb) ,ok 31 fourth
(lldb) ,ok 32 fourth
,ok 33 second
(lldb) ,ok 34 secondPromise - in then
,ok 35 first
(lldb) ,ok 36 firstPromise - in catch
,ok 37 third
,ok 38 thirdPromise - in then
(lldb) ,ok 39 testingPromises
,# teardown
(lldb) ,# setup
,# queues handled independently
(lldb) ,ok 40 all short operations completed before the long resolves
# teardown
,# setup
(lldb) ,# basic
,ok 41 sane
(lldb) ,# teardown
,# setup
(lldb) ,# another
(lldb) ,ok 42 sane
,# teardown
(lldb) ,# setup
(lldb) ,# can pass data in setup
,ok 43 test participant has uuid
(lldb) ,ok 44 participant data matches
ok 45 test participant has uuid
ok 46 participant data matches
ok 47 test participant has uuid
ok 48 participant data matches
ok 49 own UUID is found from the participants list
,# teardown
(lldb) ,# setup
,# Correctly parses/stringifies USN
(lldb) ,ok 50 correctly parses USN string
,ok 51 throws if usn has invalid prefix
ok 52 throws if usn has invalid identifier format
(lldb) ,ok 53 throws if usn has invalid generation
,ok 54 correctly stringifies peer
(lldb) ,# teardown
,# setup
(lldb) ,# onPeerLost calls jxcore
(lldb) ,2017-03-23 10:41:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-03-23 10:41:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-23 10:41:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:41:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:41:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:41:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# onPeerDiscovered calls jxcore
(lldb) ,2017-03-23 10:41:21 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-23 10:41:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 55 Can call startListeningForAdvertisements without error
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23, 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 56 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 57 Should be able to call stopListeningForAdvertisements in teardown
,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 58 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAd,vertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-03-23 10:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-23 10:41:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 59 Can call startListeningForAdvertisements without error
2017-03-23 10:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-23 ,10:41:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"(lldb) ,n,etworkType":null}})'
(lldb) ,2017-03-23 10:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 60 Can call startListeningForAdvertisements twice without error
(lldb) ,# teardown
,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 61 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:30 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-03-23 10:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-23 10:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
2017-03-23 10:41:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-03-23 10:41:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 64 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-23 10:41:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:35 -(lldb) , DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-03-23 10:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 67 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03(lldb) ,-23 10:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
,ok 69 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:40 - INFO thaliMob(lldb) ,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-03-23 10:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:41:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-(lldb) ,23 10:41:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,,"networkType":null}})'
(lldb) ,2017-03-23 10:41:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
(lldb) ,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-03-23 10:41:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:49 - DEBUG thaliMobil(lldb) ,eNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Should be able to call stopA,dvertisingAndListening in teardown
2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered (lldb) ,to native'
,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:41:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-03-23 10:42:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-23 10:42:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:42:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStat,eUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:42:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-23 10:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:42:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# peerAvailabilityChange is called
(lldb) ,2017-03-23 10:42:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:42:11 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:42:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListeningwithout error
2017-03-23 10:42:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-23,(lldb) , 10:42:11 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n,etworkType":null}})'
(lldb) ,2017-03-23 10:42:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Can call startListeningForAdvertisements without error
,ok 81 peers must be an array
ok 82 peers must not be zero-length
ok 83 peer must have only peerIdentifier, peerAvailable and generation properties
ok 84 peerIdentifier must be a string
ok 85 generation must be a number
(lldb) ,# teardown
,2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:42:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:42:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-03-23 10:42:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,b(lldb) ,ilityChanged registered to native'
,2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:42:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
,# Can connect to a remote peer
(lldb) ,2017-03-23 10:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 88 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:42:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-2,3 10:42:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,(lldb) ,",networkType":null}})'
2017-03-23 10:42:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startListeningForAdvertisements without error
(lldb) ,2017-03-23 10:42:30 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"59E2DA66-6364-4DB7-8F52-8DA1759A6190","generation":0}]'
,2017-03-23 10:42:30 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 59E2DA66-6364-4DB7-8F52-8DA1759A6190 (syncValue: 1uHisT1tk2jE7bFQodtkA4c4DmvaX92f)'
(lldb) ,2017-03-23 10:42:30 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,2017-03-23 10:42:30 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"266EF382-97B8-441A-B8EB-015D40B1F033","generation":0}]'
(lldb) ,2017-03-23 10:42:32 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"6B654D4D-913C-4A9B-9D40-65338F4A5793","generation":0}]'
(lldb) ,2017-03-23 10:42:33 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":false,"peerIdentifier":"266EF382-97B8-441A-B8EB-015D40B1F033","generation":0}]'
(lldb) ,libc++abi.dylib: terminating with uncaught exception of type NSException
(lldb) ,Process 413 stopped
* thread #29: tid = 0x9a43b, 0x00000001871a3014 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
    frame #0: 0x00000001871a3014 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x1871a3014 <+8>:  b.lo   0x1871a302c               ; <+32>
    0x1871a3018 <+12>: stp    x29, x30, [sp, #-16]!
    0x1871a301c <+16>: mov    x29, sp
    0x1871a3020 <+20>: bl     0x1871867d0               ; cerror_nocancel
(lldb) ,* thread #29: tid = 0x9a43b, 0x00000001871a3014 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
  * frame #0: 0x00000001871a3014 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x0000000187117400 libsystem_c.dylib`abort + 140
    frame #2: 0x0000000186be12d4 libc++abi.dylib`<redacted> + 132
    frame #3: 0x0000000186bfecc0 libc++abi.dylib`<redacted> + 304
    frame #4: 0x0000000186c0c844 libobjc.A.dylib`<redacted> + 124
    frame #5: 0x0000000186bfb66c libc++abi.dylib`<redacted> + 16
    frame #6: 0x0000000186bfaf84 libc++abi.dylib`__cxa_throw + 136
    frame #7: 0x0000000186c0c690 libobjc.A.dylib`objc_exception_throw + 364
    frame #8: 0x00000001880b3870 CoreFoundation`<redacted> + 312
    frame #9: 0x00000001880bf5fc CoreFoundation`<redacted> + 52
    frame #10: 0x0000000100067734 ThaliTest`-[JXcoreExtension(AppContextDelegate) context:didResolveMultiConnectWithSyncValue:error:listeningPort:] + 292
    frame #11: 0x000000010006f348 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded, Arg[2] = Owned To Guaranteed> of ThaliTest.AppContext.(handleMultiConnectResolved in _F3DAF5A2B391CB31FC98FBDA08CABB7E) (withSyncValue : Swift.String, port : Swift.Optional<Swift.UInt16>, error : Swift.Optional<Swift.Error>) -> () + 484
    frame #12: 0x0000000100071d44 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded, Arg[1] = Owned To Guaranteed, Arg[3] = Owned To Guaranteed, Arg[4] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.(multiConnectToPeer (Swift.Array<Swift.AnyObject>, validationCompletionHandler : (Swift.Optional<__ObjC.NSError>) -> ()) -> ()).(closure #1) + 124
    frame #13: 0x0000000100069b78 ThaliTest`ThaliTest.AppContext.(multiConnectToPeer (Swift.Array<Swift.AnyObject>, validationCompletionHandler : (Swift.Optional<__ObjC.NSError>) -> ()) -> ()).(closure #1) + 44
    frame #14: 0x00000001000736d0 ThaliTest`partial apply forwarder for ThaliTest.AppContext.(multiConnectToPeer (Swift.Array<Swift.AnyObject>, validationCompletionHandler : (Swift.Optional<__ObjC.NSError>) -> ()) -> ()).(closure #1) with unmangled suffix ".46" + 132
    frame #15: 0x0000000100ae1450 ThaliCore`ThaliCore.BrowserManager.(connectToPeer (Swift.String, syncValue : Swift.String, completion : (Swift.String, Swift.Optional<Swift.Error>, Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #1).(closure #1) + 156
    frame #16: 0x0000000100afc944 ThaliCore`ThaliCore.BrowserRelay.(openRelay (with : (Swift.Optional<Swift.UInt16>, Swift.Optional<Swift.Error>) -> ()) -> ()).(closure #1) + 112
    frame #17: 0x0000000100ad798c ThaliCore`ThaliCore.TCPListener.startListeningForConnections (on : Swift.UInt16, connectionAccepted : (__ObjC.GCDAsyncSocket) -> (), completion : (Swift.Optional<Swift.UInt16>, Swift.Optional<Swift.Error>) -> ()) -> () + 512
    frame #18: 0x0000000100afc7ac ThaliCore`ThaliCore.BrowserRelay.openRelay (with : (Swift.Optional<Swift.UInt16>, Swift.Optional<Swift.Error>) -> ()) -> () + 304
    frame #19: 0x0000000100ae123c ThaliCore`ThaliCore.BrowserManager.(connectToPeer (Swift.String, syncValue : Swift.String, completion : (Swift.String, Swift.Optional<Swift.Error>, Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #1) + 476
    frame #20: 0x0000000100ae13a8 ThaliCore`partial apply forwarder for ThaliCore.BrowserManager.(connectToPeer (Swift.String, syncValue : Swift.String, completion : (Swift.String, Swift.Optional<Swift.Error>, Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #1) + 176
    frame #21: 0x0000000100b3a2d4 ThaliCore`ThaliCore.Session.(session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChange : __C.MCSessionState) -> ()).(closure #1) + 348
    frame #22: 0x0000000100b3a318 ThaliCore`reabstraction thunk helper from @callee_owned (@inout __C.MCSessionState) -> (@error @owned Swift.Error) to @callee_owned (@inout __C.MCSessionState) -> (@out (), @error @owned Swift.Error) + 36
    frame #23: 0x0000000100b346c0 ThaliCore`ThaliCore.Atomic.modify <A> (action : (inout A) throws -> A1) throws -> A1 + 136
    frame #24: 0x0000000100b3a140 ThaliCore`ThaliCore.Session.session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChange : __C.MCSessionState) -> () + 664
    frame #25: 0x0000000100b3a3d0 ThaliCore`@objc ThaliCore.Session.session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChange : __C.MCSessionState) -> () + 100
    frame #26: 0x000000019cdb5960 MultipeerConnectivity`<redacted> + 148
    frame #27: 0x000000018705e1fc libdispatch.dylib`<redacted> + 24
    frame #28: 0x000000018705e1bc libdispatch.dylib`<redacted> + 16
    frame #29: 0x000000018706c3dc libdispatch.dylib`<redacted> + 928
    frame #30: 0x00000001870619a4 libdispatch.dylib`<redacted> + 652
    frame #31: 0x000000018706e34c libdispatch.dylib`<redacted> + 572
    frame #32: 0x000000018706e0ac libdispatch.dylib`<redacted> + 124
    frame #33: 0x00000001872672a0 libsystem_pthread.dylib`_pthread_wqthread + 1288

```
