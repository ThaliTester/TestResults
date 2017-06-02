#### Test 113351851cf2de5f_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851cf2de5f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,(lldb) command source -s 0 '/tmp/CE7226D6-BB73-487E-A7E9-46816674C6E1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/CE7226D6-BB73-487E-A7E9-46816674C6E1/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851cf2de5f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851cf2de5f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64884"
,(lldb)     command script import "/tmp/CE7226D6-BB73-487E-A7E9-46816674C6E1/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
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
(lldb) ,Platform ios
,Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
,JXcore engine is started
(lldb) ,2017-06-02 12:56:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 12:56:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 12:56:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 12:56:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-02 12:56:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 12:56:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 12:56:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
(lldb) ,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
(lldb) ,Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
(lldb) ,AppContextTests.test_peerAvailabilityConversion finished
(lldb) ,AppContextTests.test_disconnectErrors finished
,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-06-02 12:56:53 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.368360996246338
(lldb) ,2017-06-02 12:56:53 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
,2017-06-02 12:56:53 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-06-02 12:56:56 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-02 12:56:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-02 12:56:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-02 12:56:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-06-02 12:56:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
(lldb) ,2017-06-02 12:56:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-06-02 12:56:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
(lldb) ,2017-06-02 12:56:58 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
(lldb) ,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
(lldb) ,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
(lldb) ,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
(lldb) ,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
(lldb) ,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
,2017-06-02 12:56:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-06-02 12:56:59 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-06-02 12:56:59 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-06-02 12:57:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2,D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-02 12:57:02 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2(lldb) ,D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-02 12:57:02 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-02 12:57:08 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-06-02 12:57:08 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
(lldb) ,# closeAll can close even when connections open
(lldb) ,2017-06-02 12:57:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-06-02 12:57:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-06-02 12:57:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
(lldb) ,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-06-02 12:57:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-06-02 12:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-06-02 12:58:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-06-02 12:59:04 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-06-02 12:59:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
(lldb) ,ok 16 firstPromise result
,ok 17 firstPromise testValue
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
(lldb) ,ok 31 fourth
ok 32 fourth
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
(lldb) ,ok 40 all short operations completed before the long resolves
# teardown
(lldb) ,# setup
(lldb) ,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
(lldb) ,ok 42 executors is called
,# teardown
(lldb) ,# setup
(lldb) ,# exceptions in the executor are properly handled
(lldb) ,ok 43 got expected error
(lldb) ,# teardown
,# setup
(lldb) ,# basic
(lldb) ,ok 44 sane
(lldb) ,# teardown
,# setup
(lldb) ,# another
,ok 45 sane
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox spy
(lldb) ,2017-06-02 13:03:50 - DEBUG testTests: 'test spy method for global sinon sansbox'
(lldb) ,ok 46 test sandbox spy works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub
(lldb) ,ok 47 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub override
(lldb) ,ok 48 test sandbox stub works correctly
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox mock
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox restore after test end
(lldb) ,ok 49 test restore
(lldb) ,# teardown
,# setup
(lldb) ,# can pass data in setup
,ok 50 test participant has uuid
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
(lldb) ,2017-06-02 13:06:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-06-02 13:06:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:06:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:06:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:06:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:06:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:06:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:06:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:06:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# onPeerDiscovered calls jxcore
(lldb) ,2017-06-02 13:06:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-06-02 13:07:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:07:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:07:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:07:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:07:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:07:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:07:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:07:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-06-02 13:07:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:07:30 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:07:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
2017-06-02 13:07:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02(lldb) , 13:07:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-06-02 13:07:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:07:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:07:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:07:37 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 65 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:07:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:07:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvert,isingStateUpdateNonTCP registered to native'
2017-06-02 13:07:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:07:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:07:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:07:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:07:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:07:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
,2017-06-02 13:07:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:07:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:07:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
2017-06-02 13:07:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 ,13:07:56 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"n(lldb) ,etworkType":null}})'
2017-06-02 13:07:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
(lldb) ,# teardown
,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:08:00 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-06-02 13:08:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 70 Can call stopListeningForAdvertisements without error
2017-06-02 13:08:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:04 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-06-02 13:08:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-02 13:08:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:08:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:08:06 -(lldb) , DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:08:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:08:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:08:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:08:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:08:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-06-02 13:08:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:08:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
2017-06-02 13:08:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06,-02 13:08:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:08:11 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-06-02 13:08:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:08:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
,2017-06-02 13:08:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:08:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
(lldb) ,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-06-02 13:08:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:25 - DEBUG thaliMobil(lldb) ,eNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopA,dvertisingAndListening in teardown
2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered (lldb) ,to native'
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 82 Can call startUpdateAdvertisingAndListening without error
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 83 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:08:26 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# peerAvailabilityChange is called
,2017-06-02 13:08:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:08:27 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
2017-06-02 13:08:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-02(lldb) , 13:08:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-06-02 13:08:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
(lldb) ,ok 88 peers must be an array
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
(lldb) ,# teardown
,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:08:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-06-02 13:08:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti(lldb) ,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:08:32 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can connect to a remote peer
,2017-06-02 13:08:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can connect to a remote peer''
(lldb) ,# teardown
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 95 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:33 - INFO thaliMob(lldb) ,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can shift data
,2017-06-02 13:08:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data''
(lldb) ,# teardown
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
,ok 97 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 98 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can shift data via parallel connections
(lldb) ,2017-06-02 13:08:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data via parallel connections''
,# teardown
(lldb) ,2017-06-02 13:08:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
(lldb) ,ok 99 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:43 - INFO thaliMob,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:08:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'(lldb) ,
2017-06-02 13:08:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:08:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:08:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:08:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:08:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:08:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:08:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can shift data securely
(lldb) ,2017-06-02 13:09:00 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data securely''
,# teardown
(lldb) ,2017-06-02 13:09:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
,ok 101 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:08 - INFO thaliMo(lldb) ,bile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 102 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:09:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native',
2017-06-02 13:09:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:09:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-02 13:09:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:09:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:09:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:09:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can shift large amounts of data
(lldb) ,2017-06-02 13:09:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift large amounts of data''
,# teardown
(lldb) ,2017-06-02 13:09:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 103 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:18 - INFO thaliMo(lldb) ,bile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:09:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native',
2017-06-02 13:09:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:09:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:09:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:09:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:09:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:09:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# We do not emit peerAvailabilityChanged events until one of the start methods is called
(lldb) ,2017-06-02 13:09:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:09:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:09:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 105 Ready to advertise
2017-06-02 13:09:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-02 13:09:28 - INFO thaliMobile: 'Receiv(lldb) ,ed state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:,0(lldb) ,9:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Ready to listen
,2017-06-02 13:09:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:09:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-06-02 13:09:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 107 stop ads worked
(lldb) ,2017-06-02 13:09:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 108 test stop worked
,# teardown
(lldb) ,2017-06-02 13:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 109 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 110 Should be able to call stopAdvertisingAndListening in teard(lldb) ,own
2017-06-02 13:09:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:09:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:09:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:09:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:09:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:09:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:09:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:09:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Test updating advertising and parallel data transfer
(lldb) ,2017-06-02 13:09:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:09:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 111 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 112 Should be able to call stopAdvertisingAndListening in teard,own
2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:09:35, - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:09:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# discoveryAdvertisingStateUpdateNonTCP is called
,ok 113 discoveryActive should be false
ok 114 advertisingActive should be true
(lldb) ,ok 115 discoveryActive should be false
,ok 116 advertisingActive should be true
(lldb) ,ok 117 discoveryActive should be false
ok 118 advertisingActive should be true
,ok 119 discoveryActive should be false
ok 120 advertisingActive should be true
(lldb) ,ok 121 Can call stopAdvertisingAndListening without error
,2017-06-02 13:09:35 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/lib/Coordinated(lldb) ,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-,9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat(lldb) ,e/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":8,"ok":true,"name":"Can call stopAdvertisingAndListening without error","operator":"notOk","actual":null,"expected":false}''
,ok 122 Can call stopListeningForAdvertisements without error
(lldb) ,2017-06-02 13:09:35 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/lib/Coordinated,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-(lldb) ,9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat,e/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":9,"ok":true,"name":"Can call stopListeningForAdvertisements without error","operator":"notOk","a(lldb) ,ctual":null,"expected":false}''
,ok 123 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-06-02 13:09:35 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/lib/Coordinated,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-(lldb) ,9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat,e/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":10,"ok":true,"name":"Can call startUpdateAdvertisingAndListening without error","operator":"notO(lldb) ,k","actual":null,"expected":false}''
,ok 124 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-02 13:09:35 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/lib/Coordinated(lldb) ,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-,9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat(lldb) ,e/var/containers/Bundle/Application/D33D17BE-FC03-4A2D-9020-9239925AE983/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":11,"ok":true,"name":"Can call startListeningForAdvertisements without error","operator":"notOk",(lldb) "actual":null,"expected":false}''
,(lldb) ,# teardown
,ok 125 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,ok 126 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:09:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# cannot call connect when start listening for advertisements is not active
(lldb) ,2017-06-02 13:09:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
(lldb) ,2017-06-02 13:09:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 127 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 128 Should be able to call stopAdvertisingAndListening in teard(lldb) own
(lldb) ,# setup
,# Get error when trying to double connect to a peer on Android
(lldb) ,2017-06-02 13:09:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
,# teardown
(lldb) ,2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
(lldb) ,ok 129 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:40 - INFO thaliMo,bile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,# setup
,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
(lldb) ,2017-06-02 13:09:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
,# teardown
(lldb) ,2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:09:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,# setup
(lldb) ,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
,2017-06-02 13:09:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
(lldb) ,# teardown
,2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 134 Should be able to call stopAdvertisingAndListening in teard(lldb) ,own
,# setup
(lldb) ,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-06-02 13:09:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
(lldb) ,# teardown
(lldb) ,2017-06-02 13:09:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 135 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 136 Should be able to call stopAdvertisingAndListening in teardown
,# setup
(lldb) ,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-06-02 13:09:45 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
(lldb) ,# teardown
,2017-06-02 13:09:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 137 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 138 Should be able to call stopAdvertisingAndListening in teard(lldb) ,own
,# setup
(lldb) ,# cannot call multiConnect when start listening for advertisements is not active
(lldb) ,ok 139 Got null as expected
(lldb) ,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"iu4rhfFdMpiiSP82SrPVlbhU2fAR1Srp","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 140 Should only get called after multiConnect retur(lldb) ,ned
ok 141 SyncValue matches
ok 142 Got right error
ok 143 listeningPort is null
2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"d93a3929-c6d3-4c71-8e4b-b31921aeb6a6","peerAvailabl,e":false,"portNumber":null,"recreated":true}'
2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
(lldb) ,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"d93a3929-c6d3-4c71-8e4b-b31921aeb6a6","peerAvailable":true,"portNumber":null,"recreated":true}'
,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
(lldb) ,# teardown
,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 144 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 145 Should be able to call stopAdvertisingAndListening in teard,own
2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:09:49(lldb) , - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:09:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# cannot call multiConnect with illegal peerID
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-02 13:09:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
,2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 146 No error on starting
,ok 147 Got null as expected
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"IBA3eZqrQBrfjKe9SrtsMmNHiVdpYY9U","error":"Illegal peerID","portNumber":null}'
,ok 148 Should only get called after multiConnect returned
(lldb) ,ok 149 SyncValue matches
,ok 150 Got right error
(lldb) ,ok 151 listeningPort is null
,# teardown
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 152 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 153 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# multiConnect properly fails on legal but non-existent peerID
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:09:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 154 No error on starting
ok 155 Got null as expected
2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"GBlUplzVOQyptUu09eawfq3jCPtvVdWp","error":"Connection could not be esta,blished","portNumber":null}'
(lldb) ,ok 156 Should only get called after multiConnect returned
,ok 157 SyncValue matches
(lldb) ,ok 158 Got right error
ok 159 listeningPort is null
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8f03d110-01ec-42d2-bcb9-539729a0c1c5","peerAvailable":false,"portNumber":null,"recreated":true}'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"8f03d110-01ec-42d2-bcb9-539729a0c1c5","peerAvailable":true,"portNumber":null,"recreated":true}'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 160 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:50 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 161 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat,ive'
2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# cannot call multiConnect with invalid syncValue
(lldb) ,2017-06-02 13:10:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:10:09 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:10:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 162 No error on starting
ok 163 Got right error
,# teardown
,2017-06-02 13:10:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:10:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 164 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:10:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:10:15 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 165 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:10:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
2017-06-02 13:10:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:10:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:10:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:10:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:10:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:10:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:10:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# disconnect doesn't fail on bad peer id
(lldb) ,ok 166 No error
(lldb) ,# teardown
,2017-06-02 13:10:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:10:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
,ok 167 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:10:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:10:42 - INFO thaliMo(lldb) ,bile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 168 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:10:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native',
2017-06-02 13:10:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:10:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:10:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:10:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:10:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:10:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:10:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# disconnect doesn't fail on plausible but bogus peer ID
(lldb) ,ok 169 No error
(lldb) ,# teardown
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) .'
(lldb) ,ok 170 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 171 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Get same port when trying to connect multiple times on iOS
(lldb) ,2017-06-02 13:11:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
,# teardown
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 172 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 173 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# initial peer discovery
(lldb) ,2017-06-02 13:11:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'initial peer discovery''
,# teardown
(lldb) ,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:11:03 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:11:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# update peer discovery 1
,2017-06-02 13:11:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
(lldb) ,# teardown
(lldb) ,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:11:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
(lldb) ,# update peer discovery 2
,2017-06-02 13:11:07 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
(lldb) ,# teardown
(lldb) ,2017-06-02 13:11:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:11:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:11:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:11:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:11:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:11:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:11:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:11:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# check latest peer discovery
(lldb) ,2017-06-02 13:11:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
(lldb) ,2017-06-02 13:11:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:11:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:11:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:11:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:11:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:11:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:11:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:11:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Set up for no peer discovery test
(lldb) ,2017-06-02 13:11:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
,# teardown
(lldb) ,2017-06-02 13:12:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:12:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:12:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:12:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:12:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:12:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:12:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:12:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# no peer discovery
(lldb) ,2017-06-02 13:12:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
,# teardown
(lldb) ,2017-06-02 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:12:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:12:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:12:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# calling createNativeListener directly rejects
,2017-06-02 13:12:20 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:12:20 - DEBUG createNativeListener: 'listening 50861'
ok 174 Should throw
,# teardown
,2017-06-02 13:12:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:12:20 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# emits incomingConnectionState
(lldb) ,2017-06-02 13:12:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:12:21 - DEBUG createNativeListener: 'listening 50863'
,2017-06-02 13:12:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
(lldb) ,2017-06-02 13:12:21 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 175 initial connection state should be CONNECTED
(lldb) ,2017-06-02 13:12:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 176 final connection state should be DISCONNECTED
(lldb) ,# teardown
,2017-06-02 13:12:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:12:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:23 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# emits routerPortConnectionFailed
(lldb) ,2017-06-02 13:12:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:44 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:12:44 - DEBUG createNativeListener: 'listening 50866'
,2017-06-02 13:12:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
(lldb) ,2017-06-02 13:12:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-02 13:12:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,2017-06-02 13:12:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 177 tried to connect to right port
(lldb) ,ok 178 failed due to refused connection
(lldb) ,ok 179 routerPortConnectionFailed is emitted
,# teardown
(lldb) ,2017-06-02 13:12:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-02 13:12:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-02 13:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Native Server - close'
2017-06-02 13:12:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-06-02 13:12:49 - DEBUG createNativeListener: 'incoming ,- incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
(lldb) ,# native server connections all up
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'listening 50870'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 180 Send/recvd #1 should be equal length
(lldb) ,ok 181 Send/recvd #1 should be same
,ok 182 Send/recvd #2 should be equal length
(lldb) ,ok 183 Send/recvd #2 should be same
,ok 184 Should be exactly 2 client sockets
(lldb) ,# teardown
,2017-06-02 13:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# setup
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'listening 50875'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 185 socket shouldn't close until after stream
(lldb) ,ok 186 incoming remains open
,# teardown
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-02 13:12:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:12:50 - DEBUG createNativeListener: 'Native Server - close'
2017-06-02 13:12:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-06-02 13:12:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# setup
,# native server - closing incoming connection cleans outgoing socket
(lldb) ,2017-06-02 13:12:54 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:12:54 - DEBUG createNativeListener: 'listening 50879'
(lldb) ,2017-06-02 13:12:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
(lldb) ,2017-06-02 13:12:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 187 we should not have gotten an error
(lldb) ,2017-06-02 13:12:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-02 13:12:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-02 13:12:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 188 socket shouldn't close until after incoming
,ok 189 incoming is cleaned up
(lldb) ,# teardown
,2017-06-02 13:12:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,2017-06-02 13:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:13:04 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# native server - closing outgoing socket cleans associated mux stream
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:13:18 - DEBUG createNativeListener: 'listening 50889'
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-02 13:13:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-02 13:13:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
,2017-06-02 13:13:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,ok 190 stream was closed
(lldb) ,ok 191 incoming should survive
,ok 192 mux should have no streams
(lldb) ,# teardown
,2017-06-02 13:13:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:13:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:13:18 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-02 13:13:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# setup
,# native server - closing the whole server cleans everything up
(lldb) ,2017-06-02 13:13:19 - DEBUG createNativeListener: 'Creating Native Server'
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'listening 50893'
(lldb) ,2017-06-02 13:13:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 193 we should not have gotten an error
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,ok 194 Buffers are identical
,2017-06-02 13:13:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:13:19 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,2017-06-02 13:13:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 195 native server is nulled out
ok 196 native server should be closed
(lldb) ,ok 197 incoming has been removed
,ok 198 Incoming should be done
(lldb) ,ok 199 The mux object should be closed
,ok 200 The mux stream should be closed
(lldb) ,2017-06-02 13:13:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# teardown
(lldb) ,2017-06-02 13:13:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-02 13:13:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# setup
,# native server - we can get a ton of connections and data through and still clean up the server completely
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'listening 50900'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
,2017-06-02 13:13:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'Native Server - close'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
(lldb) ,2017-06-02 13:13:23 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
,2017-06-02 13:13:23 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
(lldb) ,ok 201 native server is nulled out
,ok 202 native server should be closed
(lldb) ,ok 203 incoming has been removed
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,# teardown
,2017-06-02 13:13:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
(lldb) ,2017-06-02 13:13:49 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:13:49 - DEBUG createNativeListener: 'listening 50954'
,2017-06-02 13:13:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-02 13:13:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 204 we should not have gotten an error
,2017-06-02 13:13:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,ok 205 Buffers are identical
,2017-06-02 13:13:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-02 13:13:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-02 13:13:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 206 server should be fine
,ok 207 server should be open
(lldb) ,ok 208 incoming has been removed
,ok 209 The mux object should be closed
(lldb) ,ok 210 The mux stream should be closed
,2017-06-02 13:13:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,# teardown
,2017-06-02 13:14:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:14:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:14:00 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# native server - timing out the incoming connection cleans everything up
(lldb) ,2017-06-02 13:14:15 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:14:15 - DEBUG createNativeListener: 'listening 50958'
(lldb) ,2017-06-02 13:14:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-02 13:14:15 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 211 we should not have gotten an error
,2017-06-02 13:14:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,ok 212 Buffers are identical
,2017-06-02 13:14:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
(lldb) ,2017-06-02 13:14:15 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-02 13:14:15 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-02 13:14:15 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 213 server should be fine
,ok 214 server should be open
(lldb) ,ok 215 incoming has been removed
,ok 216 The mux object should be closed
(lldb) ,ok 217 The mux stream should be closed
,# teardown
(lldb) ,2017-06-02 13:14:15 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-02 13:14:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:14:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:14:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# can create servers manager
,ok 218 serversManager must not be null
(lldb) ,ok 219 serversManager must be an object
,# teardown
(lldb) ,# setup
(lldb) ,# calling stop without start causes error
,ok 220 We need to call start first
(lldb) ,# teardown
,# setup
(lldb) ,# can start/stop servers manager
(lldb) ,2017-06-02 13:15:09 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:15:09 - DEBUG createNativeListener: 'listening 50964'
ok 221 port must be in range
,# teardown
(lldb) ,2017-06-02 13:15:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:15:16 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# starting twice resolves with listening port
(lldb) ,2017-06-02 13:15:20 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:15:20 - DEBUG createNativeListener: 'listening 50965'
ok 222 second start should return same port
,# teardown
(lldb) ,2017-06-02 13:15:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:15:29 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# terminateIncomingConnection will terminate a connection
(lldb) ,2017-06-02 13:15:54 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:15:54 - DEBUG createNativeListener: 'listening 50967'
(lldb) ,2017-06-02 13:15:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-02 13:15:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 223 we should be connected
,2017-06-02 13:15:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 224 now we are disconnected
,2017-06-02 13:15:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# teardown
,2017-06-02 13:15:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:15:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
,# terminate an Outgoing connection
(lldb) ,2017-06-02 13:16:00 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
(lldb) ,ok 225 Passed bogus id
,2017-06-02 13:16:00 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
(lldb) ,ok 226 Passed good id but bogus port
,2017-06-02 13:16:00 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
(lldb) ,ok 227 Passed right context
,ok 228 Right server
,ok 229 No error should be set
(lldb) ,ok 230 Retry should be false
,ok 231 We called close server
(lldb) ,# teardown
,# setup
(lldb) ,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# #startListeningForAdvertisements should fail if start not called
,ok 232 specific error should be returned
(lldb) ,# teardown
,ok 233 must be stopped
(lldb) ,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:06 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:16:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-02 13:16:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:08 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:08 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 234 specific error should be returned
(lldb) ,# teardown
,ok 235 must be stopped
(lldb) ,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-02 13:16:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #stopListeningForAdvertisements many times
,2017-06-02 13:16:20 - DEBUG thaliMobileNativeWrapper: 'listening 50969'
(lldb) ,2017-06-02 13:16:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:16:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 236 no errors
,2017-06-02 13:16:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:16:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 237 still no errors
(lldb) ,# teardown
,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-06-02 13:16:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 238 must be stopped
,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #startListeningForAdvertisements many times
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'listening 50974'
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-02 13:16:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 239 no errors
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-06-02 13:16:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 240 still no errors
(lldb) ,# teardown
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-06-02 13:16:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,2017-06-02 13:16:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 241 must be stopped
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:16:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #startUpdateAdvertisingAndListening many times
(lldb) ,2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'listening 50977'
,2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:16:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-06-02 13:16:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 242 no errors
,2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-06-02 13:16:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-06-02 13:16:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 243 still no errors
,# teardown
(lldb) ,2017-06-02 13:16:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:16:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
2017-06-02 13:16:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:16:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped st,ate).'
2017-06-02 13:16:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 244 must be stopped
2017-06-02 13:16:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:16:56 - DEBUG thaliM(lldb) ,obileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:16:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:16:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:16:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:16:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:16:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:16:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:17:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:17:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:17:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:17:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #stopAdvertisingAndListening many times

```
