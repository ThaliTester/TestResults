#### Test 11335185197c53a1_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/11335185197c53a1/build_ios/ThaliTest.app
,------ Debug phase ------
Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/F59BA2B8-7596-43FA-A6E4-1DD6B2158B37/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/F59BA2B8-7596-43FA-A6E4-1DD6B2158B37/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/11335185197c53a1/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/11335185197c53a1/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51618"
,(lldb)     command script import "/tmp/F59BA2B8-7596-43FA-A6E4-1DD6B2158B37/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
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
,2017-05-30 12:49:27 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-30 12:49:27 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-30 12:49:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-30 12:49:27 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-30 12:49:27 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-30 12:49:27 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-30 12:49:27 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
Optional(true)
Optional(false)
,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo(lldb) ,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-05-30 12:49:30 - DEBUG UnitTest_app: 'Running unit tests'
(lldb) ,*Native tests were executed*
,Total number of executed tests:  13
(lldb) ,Number of passed tests:  13
,Number of failed tests:  0
(lldb) ,Number of ignored tests:  0
,Total duration:  1.752463161945343
(lldb) ,2017-05-30 12:49:30 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-05-30 12:49:30 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-05-30 12:49:33 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-30 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-30 12:49:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-30 12:49:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-05-30 12:49:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-05-30 12:49:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-30 12:49:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-05-30 12:49:37 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-05-30 12:49:37 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-05-30 12:49:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-30 12:49:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:49:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:49:48 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-05-30 12:49:48 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-05-30 12:50:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
,# teardown
,# setup
(lldb) ,# closeAll with promise
,2017-05-30 12:50:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
,(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-05-30 12:50:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-05-30 12:51:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-05-30 12:51:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-05-30 12:51:48 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-05-30 12:52:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-05-30 12:52:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
(lldb) ,ok 4 should be equal
ok 5 should be equal
(lldb) ,ok 6 should be equal
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultAdapter
,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
(lldb) ,ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
,# teardown
(lldb) ,# setup
,# enqueue and run in order
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
,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
(lldb) ,# teardown
,# setup
(lldb) ,2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
(lldb) ,2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-05-30 12:55:28 - INFO Coord(lldb) ,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-05(lldb) ,-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGG,ER result: passed - enqueue and run in order'
2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-05-30 12:55:28 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - mix enqueue and en(lldb) ,queueAtTop, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afte,rTimeout@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1(lldb) ,CD3E544979/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-05-30 12:55:28 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
(lldb) ,2017-05-30 12:55:45 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-05-30 12:55:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:55:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:55:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:55:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:55:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:55:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:56:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:56:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-30 12:56:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:56:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:56:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:56:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:56:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:56:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-30 12:56:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:56:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:57:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:57:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:57:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:57:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:57:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:57:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4(lldb) ,314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var(lldb) ,/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-30 12:57:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-431(lldb) ,4-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-30 12:57:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/5F3CB370-53F1-4314-B7A6-C1CD3E544979/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-30 12:58:30 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-05-30 12:58:30 - DEBUG CoordinatedClient: 'test client failed'
2017-05-30 12:58:30 - ERROR CoordinatedClient: 'reconnect_er(lldb) ,ror error: 'timeout', description: 'undefined', stack: 'undefined''
2017-05-30 12:58:30 - DEBUG CoordinatedClient: 'test client failed'
(lldb) ,2017-05-30 12:58:30 - DEBUG CoordinatedClient: '50000'
2017-05-30 12:58:30 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-05-30 12:58:30 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
```
