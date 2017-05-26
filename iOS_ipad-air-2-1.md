#### Test 113351851b96d414_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851b96d414/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/55C61B81-296F-4288-826C-60D14BE2D05F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/55C61B81-296F-4288-826C-60D14BE2D05F/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851b96d414/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851b96d414/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57838"
,(lldb)     command script import "/tmp/55C61B81-296F-4288-826C-60D14BE2D05F/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-05-26 06:19:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-26 06:19:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-26 06:19:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-26 06:19:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-26 06:19:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-26 06:19:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-26 06:19:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
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
(lldb) ,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-05-26 06:19:46 - DEBUG UnitTest_app: 'Running unit tests'
(lldb) ,*Native tests were executed*
Total number of executed tests:  13
,Number of passed tests:  13
(lldb) ,Number of failed tests:  0
,Number of ignored tests:  0
(lldb) ,Total duration:  1.298112094402313
,2017-05-26 06:19:46 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
(lldb) ,2017-05-26 06:19:46 - WARN testUtils: 'myNameCallback not set!'
,2017-05-26 06:19:49 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-26 06:19:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-05-26 06:19:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-05-26 06:19:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
,2017-05-26 06:19:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
(lldb) ,2017-05-26 06:19:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
,2017-05-26 06:19:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
(lldb) ,2017-05-26 06:19:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-05-26 06:19:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
(lldb) ,2017-05-26 06:19:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-05-26 06:19:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
(lldb) ,2017-05-26 06:19:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-05-26 06:19:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
(lldb) ,2017-05-26 06:19:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-05-26 06:19:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
(lldb) ,2017-05-26 06:19:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-05-26 06:19:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-05-26 06:19:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-26 06:19:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-05-26 06:19:52 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-05-26 06:19:52 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-05-26 06:19:53 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-05-26 06:20:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-05-26 06:20:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-05-26 06:20:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-05-26 06:20:33 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-05-26 06:20:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-05-26 06:20:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-05-26 06:20:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-05-26 06:20:42 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
,# test defaultDirectory
(lldb) ,ok 4 should be equal
ok 5 should be equal
ok 6 should be equal
,# teardown
(lldb) ,# setup
,# test defaultAdapter
(lldb) ,ok 7 should be equal
,ok 8 should be equal
(lldb) ,ok 9 should be equal
,ok 10 should be equal
(lldb) ,ok 11 should be equal
,ok 12 should be equal
(lldb) ,ok 13 should be equal
,ok 14 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# enqueue and run in order
,ok 15 firstPromise setTimeout
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
,ok 24 thirdPromise - first to run
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
# teardown
(lldb) ,# setup
,# queues handled independently
(lldb) ,ok 40 all short operations completed before the long resolves
# teardown
,# setup
(lldb) ,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
,ok 42 executors is called
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
(lldb) ,2017-05-26 06:21:36 - DEBUG testTests: 'test spy method for global sinon sansbox'
,ok 46 test sandbox spy works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub
,ok 47 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub override
,ok 48 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox mock
(lldb) ,# teardown
(lldb) ,# setup
,# test sinon sansbox restore after test end
(lldb) ,ok 49 test restore
,# teardown
(lldb) ,# setup
,# can pass data in setup
(lldb) ,ok 50 test participant has uuid
ok 51 participant data matches
ok 52 test participant has uuid
ok 53 participant data matches
ok 54 test participant has uuid
ok 55 participant data matches
ok 56 own UUID is found from the participants list
,# teardown
(lldb) ,# setup
,# Correctly parses/stringifies USN
(lldb) ,ok 57 correctly parses USN string
,ok 58 throws if usn has invalid prefix
(lldb) ,ok 59 throws if usn has invalid identifier format
,ok 60 throws if usn has invalid generation
(lldb) ,ok 61 correctly stringifies peer
,# teardown
(lldb) ,# setup
,# onPeerLost calls jxcore
(lldb) ,2017-05-26 06:21:46 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-05-26 06:21:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-26 06:21:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-26 06:21:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-26 06:21:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-26 06:21:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-26 06:21:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-26 06:21:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-26 06:21:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# onPeerDiscovered calls jxcore
(lldb) ,2017-05-26 06:21:50 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-05-26 06:21:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-05-26 06:21:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-26 06:21:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-26 06:21:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-05-26 06:21:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2017-05-26 06:21:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-26 06:21:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-26 06:21:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
(lldb) ,# Can call start/stopListeningForAdvertisements
,2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-05-26 06:21:51 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
,2017-05-26 06:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 62 Can call startListeningForAdvertisements without error
,2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-26 06:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 63 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-26 06:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-26 06:21:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-26 06:21:51 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-26 06:21:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-26 06:21:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-05-26 06:22:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-05-26 06:22:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-05-26 06:22:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
(lldb) ,2017-05-26 06:22:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-05-26 06:22:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
,2017-05-26 06:22:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-05-26 06:22:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-26 06:22:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 68 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-05-26 06:22:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-05-26 06:22:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 69 Should be able to call stopAdvertisingAndListening in teardown
,2017-05-26 06:22:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-26 06:22:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-26 06:22:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-26 06:22:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-26 06:22:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-26 06:22:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-26 06:22:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-26 06:22:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
,2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-26 06:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 70 Can call stopListeningForAdvertisements without error
2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-26 06:22:30 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-26 06:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-26 06:22:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-26 06:22:30 -(lldb) , DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-26 06:22:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-26 06:22:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-05-26 06:22:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-26 06:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-26 06:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-05-26 06:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 76 Should be able to call stopListeningForAdvertisements in teardown
,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-26 06:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-26 06:22:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-05-26 06:22:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-26 06:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 78 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-05-26 06:22:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-05-26 06:22:34 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
,2017-05-26 06:22:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 79 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
(lldb) ,2017-05-26 06:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-05-26 06:22:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-05-26 06:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,2017-05-26 06:22:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-26 06:22:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 81 Should be able to call stopAdvertisingAndListening in teardown
,2017-05-26 06:22:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-26 06:22:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-26 06:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-26 06:22:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-26 06:22:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-26 06:22:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-26 06:22:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-26 06:22:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2017-05-26 06:22:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-26 06:22:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-05-26 06:22:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-05-26 06:22:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-05-26 06:22:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-26 06:22:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
2017-05-26 06:22:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-26 06:22:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-05-26 06:22:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-26 06:22:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-26 06:22:41 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-26 06:22:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-26 06:22:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-26 06:22:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-26 06:22:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-26 06:22:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# peerAvailabilityChange is called
(lldb) ,2017-05-26 06:22:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-05-26 06:22:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-26 06:22:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
2017-05-26 06:22:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-05-26(lldb) , 06:22:44 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-05-26 06:22:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
,ok 88 peers must be an array
(lldb) ,ok 89 peers must not be zero-length
,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
(lldb) ,ok 91 peerIdentifier must be a string
,ok 92 generation must be a number
(lldb) ,# teardown
,2017-05-26 06:22:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-05-26 06:22:50 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-05-26 06:22:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
2017-05-26 06:22:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti(lldb) ,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-26 06:22:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-05-26 06:22:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-05-26 06:22:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-26 06:22:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-26 06:22:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-26 06:22:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-26 06:22:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-26 06:22:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-26 06:22:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can connect to a remote peer
(lldb) ,2017-05-26 06:22:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-05-26 06:22:57 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-26 06:22:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 95 Can call startUpdateAdvertisingAndListening without error
2017-05-26 06:22:57 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
(lldb) ,2017-05-26 06:22:57 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-05-26 06:22:57 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
(lldb) ,2017-05-26 06:22:58 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"3AB915AC-1204-4C55-A979-E40920593FF0","generation":0}]'
,2017-05-26 06:22:58 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 3AB915AC-1204-4C55-A979-E40920593FF0 (syncValue: q86i1sSTl4irX45dzrUmq4ZFRGStUiq2)'
(lldb) ,2017-05-26 06:22:58 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,2017-05-26 06:22:58 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"B7B31C99-670A-4E19-A636-BA646B7049A5","generation":0}]'
(lldb) ,2017-05-26 06:22:59 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"6CDACF74-3C19-4172-8FFA-A20CC359AE4A","generation":0}]'
,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
(lldb) ,2017-05-26 06:23:20 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":false,"peerIdentifier":"3AB915AC-1204-4C55-A979-E40920593FF0","generation":0}]'
(lldb) ,2017-05-26 06:25:53 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-05-26 06:25:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:25:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:25:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:25:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:26:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:26:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:26:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:26:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:26:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:26:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:26:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:26:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:26:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:26:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:27:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:27:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:27:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:27:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:27:22 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:27:22 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:27:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:27:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:27:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:27:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:27:53 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:27:53 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:28:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:28:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:28:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:28:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:28:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:28:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:28:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:28:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:28:44 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:28:44 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:29:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:29:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:29:32 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:29:32 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:30:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:30:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-05-26 06:30:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-407(lldb) ,1-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-05-26 06:30:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E5CCF008-A66B-4071-9AAD-953CCF673AAC/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-05-26 06:31:55 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-05-26 06:31:55 - DEBUG CoordinatedClient: 'test client failed'
2017-05-26 06:31:55 - ERROR CoordinatedClient: 'reconnect_er(lldb) ,ror error: 'timeout', description: 'undefined', stack: 'undefined''
2017-05-26 06:31:55 - DEBUG CoordinatedClient: 'test client failed'
,2017-05-26 06:31:55 - DEBUG CoordinatedClient: '50000'
2017-05-26 06:31:55 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-05-26 06:31:55 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'(lldb) 
```
