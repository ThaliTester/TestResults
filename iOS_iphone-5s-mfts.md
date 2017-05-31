#### Test 1133518514d49fb2_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1133518514d49fb2/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/31AD79DA-2135-43AA-8289-47C49B3A6F17/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/31AD79DA-2135-43AA-8289-47C49B3A6F17/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1133518514d49fb2/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1133518514d49fb2/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:56818"
,(lldb)     command script import "/tmp/31AD79DA-2135-43AA-8289-47C49B3A6F17/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
(lldb)     connect
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
,2017-05-31 11:53:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-31 11:53:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-31 11:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-31 11:53:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-31 11:53:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-31 11:53:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-31 11:53:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
(lldb) ,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
(lldb) ,AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-05-31 11:53:03 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.429419934749603
,2017-05-31 11:53:04 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
(lldb) ,2017-05-31 11:53:04 - WARN testUtils: 'myNameCallback not set!'
,2017-05-31 11:53:07 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-31 11:53:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-31 11:53:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-31 11:53:07 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-31 11:53:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-05-31 11:53:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-05-31 11:53:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-05-31 11:53:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-05-31 11:53:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-05-31 11:53:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-05-31 11:53:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-31 11:53:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-05-31 11:53:11 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-05-31 11:53:11 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-05-31 11:53:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 11:53:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 11:53:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 11:53:20 - DEBUG CoordinatedClient: 'reconnected to the test server'
(lldb) ,2017-05-31 11:53:20 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-05-31 11:53:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
# teardown
(lldb) ,# setup
(lldb) ,# closeAll with promise
,2017-05-31 11:53:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-05-31 11:53:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-05-31 11:54:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
,2017-05-31 11:54:08 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
(lldb) ,# teardown
,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-05-31 11:54:11 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-05-31 11:54:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-05-31 11:54:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
(lldb) ,ok 4 should be equal
(lldb) ,ok 5 should be equal
ok 6 should be equal
,# teardown
(lldb) ,# setup
,# test defaultAdapter
(lldb) ,ok 7 should be equal
,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
(lldb) ,ok 13 should be equal
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
,# teardown
(lldb) ,# setup
(lldb) ,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
(lldb) ,# setup
(lldb) ,# enqueued function are always executed asynchronously
,ok 41 executor is not called here
(lldb) ,ok 42 executors is called
,# teardown
(lldb) ,# setup
,# exceptions in the executor are properly handled
,ok 43 got expected error
(lldb) ,# teardown
,# setup
(lldb) ,# basic
(lldb) ,ok 44 sane
,# teardown
(lldb) ,# setup
(lldb) ,# another
(lldb) ,ok 45 sane
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox spy
(lldb) ,2017-05-31 11:55:13 - DEBUG testTests: 'test spy method for global sinon sansbox'
ok 46 test sandbox spy works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub
(lldb) ,ok 47 test sandbox stub works correctly
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox stub override
,ok 48 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox mock
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox restore after test end
(lldb) ,ok 49 test restore
,# teardown
(lldb) ,# setup
(lldb) ,# can pass data in setup
(lldb) ,ok 50 test participant has uuid
ok 51 participant data matches
ok 52 test participant has uuid
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
(lldb) ,ok 56 own UUID is found from the participants list
,# teardown
(lldb) ,# setup
(lldb) ,# Correctly parses/stringifies USN
(lldb) ,ok 57 correctly parses USN string
(lldb) ,ok 58 throws if usn has invalid prefix
,ok 59 throws if usn has invalid identifier format
(lldb) ,ok 60 throws if usn has invalid generation
(lldb) ,ok 61 correctly stringifies peer
,# teardown
(lldb) ,# setup
,# onPeerLost calls jxcore
(lldb) ,2017-05-31 11:56:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-05-31 11:57:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-31 11:57:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-31 11:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-31 11:57:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-31 11:57:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-31 11:57:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-31 11:57:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-31 11:57:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# onPeerDiscovered calls jxcore
(lldb) ,2017-05-31 11:57:09 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-05-31 11:57:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-31 11:57:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-31 11:57:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-31 11:57:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-31 11:57:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-31 11:57:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-31 11:57:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-31 11:57:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopListeningForAdvertisements
,2017-05-31 11:57:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-31 11:57:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-31 11:57:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
2017-05-31 11:57:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-31, 11:57:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-05-31 11:57:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-31 11:57:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-05-31 11:57:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-31 11:57:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-05-31 11:57:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-31 11:57:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-31 11:57:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-31 11:57:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-31 11:57:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-31 11:57:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-31 11:57:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-31 11:57:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
,2017-05-31 11:57:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-31 11:57:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-05-31 11:57:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 66 Can call startListeningForAdvertisements without error
,2017-05-31 11:57:38 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-05-31 11:57:38 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-05-31 11:57:38 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 67 Can call startListeningForAdvertisements twice without error
(lldb) ,# teardown
,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
(lldb) ,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-05-31 11:58:38 - INFO Coord(lldb) ,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes, that are in the checkpoints plugin delay interval'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-05(lldb) ,-,31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGE(lldb) ,R result: passed - enqueue and run in order'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enq,ueueAtTop'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously'
(lldb) ,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-05-31 11:58:38 - INFO CoordinatedC,lient: '***TEST_LOGGER result: passed - another'
(lldb) ,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
(lldb) ,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
(lldb) ,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
(lldb) ,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
(lldb) ,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
(lldb) ,2017-05-31 11:58:38 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Calling startListeningForAdvertisements twice is NOT an error, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/92CBADCB(lldb) ,-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules,/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
(lldb) ,2017-05-31 11:58:38 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
,2017-05-31 12:00:23 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-05-31 12:00:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:00:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:00:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:00:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:00:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:00:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:00:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:00:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:00:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:00:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:01:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:01:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:01:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:01:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:01:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:01:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:01:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:01:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:01:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:01:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:01:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:01:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:02:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:02:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:02:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:02:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:02:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:02:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:02:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:02:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:02:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:02:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:02:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:02:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:03:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:03:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:03:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:03:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:03:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:03:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:03:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:03:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:03:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:03:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:04:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:04:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:04:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:04:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:04:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:04:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:04:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:04:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:04:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:04:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:04:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:04:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:05:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:05:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:05:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:05:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:05:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:05:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:05:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:05:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:05:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:05:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:05:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:05:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:06:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:06:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:06:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:06:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:06:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:06:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:06:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:06:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:06:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:06:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:06:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:06:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:07:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:07:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:07:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:07:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:07:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:07:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:07:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:07:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:07:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:07:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:07:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:07:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:08:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:08:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:08:23 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:08:23 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:08:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:08:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:08:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:08:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:08:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:08:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-4(lldb) ,99B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/nod(lldb) ,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:09:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:09:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:09:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:09:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:09:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:09:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:09:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:09:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:09:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:09:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:09:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:09:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:10:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:10:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:10:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:10:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:10:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:10:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:11:04 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:11:04 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:11:14 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:11:14 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:11:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:11:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:11:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:11:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:11:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:11:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:11:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:11:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:12:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:12:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:12:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:12:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:12:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:12:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:12:37 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:12:37 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-31 12:12:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:12:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:12:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:12:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-31 12:13:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499(lldb) ,B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-31 12:13:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/92CBADCB-0E61-499B-BB58-07819A71470A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) 
```
