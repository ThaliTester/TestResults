#### Test 112800850f460826_iOS_ipad-air-2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/112800850f460826/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,(lldb) command source -s 0 '/tmp/20A15D53-1787-470A-A27A-6BC9BF35B40D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/20A15D53-1787-470A-A27A-6BC9BF35B40D/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/112800850f460826/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/112800850f460826/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:51026"
,(lldb)     command script import "/tmp/20A15D53-1787-470A-A27A-6BC9BF35B40D/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
(lldb) ,JXcore engine is ready
,Starting JXcore engine
(lldb) ,Platform ios
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
(lldb) ,2017-03-28 11:03:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-28 11:03:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-28 11:03:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 11:03:31 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 11:03:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 11:03:31 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 11:03:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
(lldb) ,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
(lldb) ,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
(lldb) ,AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
(lldb) ,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,Optional(false)
Optional(true)
,AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
(lldb) AppContextTests.test_peerAvailabilityConversion finished
,(lldb) ,AppContextTests.test_disconnectErrors finished
(lldb) ,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-03-28 11:03:33 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
(lldb) ,Number of ignored tests:  0
Total duration:  1.307381153106689
(lldb) ,2017-03-28 11:03:33 - DEBUG UnitTest_app: 'My device name is: 'Apple-ipad-air-2-1''
,2017-03-28 11:03:33 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-03-28 11:03:35 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-28 11:03:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-28 11:03:35 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
(lldb) ,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
(lldb) ,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
(lldb) ,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
(lldb) ,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-03-28 11:03:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-28 11:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-28 11:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-28 11:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-28 11:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-28 11:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-28 11:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-28 11:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-28 11:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-28 11:03:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-28 11:03:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-28 11:03:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/D21EF5F0-48BA-4DC3-A31D-157636A7854C/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-28 11:03:39 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
(lldb) ,appEnteredForeground wasn't registered
,2017-03-28 11:03:39 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
(lldb) ,2017-03-28 11:03:39 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-03-28 11:04:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-03-28 11:04:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-03-28 11:04:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
# teardown
(lldb) ,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-03-28 11:04:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-03-28 11:04:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-03-28 11:04:31 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-03-28 11:04:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-03-28 11:04:40 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
,ok 4 should be equal
(lldb) ,ok 5 should be equal
,ok 6 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
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
(lldb) ,# setup
,# can pass data in setup
(lldb) ,ok 46 test participant has uuid
(lldb) ,ok 47 participant data matches
ok 48 test participant has uuid
ok 49 participant data matches
ok 50 test participant has uuid
ok 51 participant data matches
ok 52 own UUID is found from the participants list
,# teardown
(lldb) ,# setup
,# Correctly parses/stringifies USN
(lldb) ,ok 53 correctly parses USN string
ok 54 throws if usn has invalid prefix
ok 55 throws if usn has invalid identifier format
(lldb) ,ok 56 throws if usn has invalid generation
,ok 57 correctly stringifies peer
(lldb) ,# teardown
,# setup
(lldb) ,# onPeerLost calls jxcore
,2017-03-28 11:05:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
(lldb) ,# teardown
,2017-03-28 11:05:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 11:05:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-28 11:05:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 11:05:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 11:05:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-28 11:05:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 11:05:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 11:05:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# onPeerDiscovered calls jxcore
(lldb) ,2017-03-28 11:05:53 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-03-28 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-28 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 11:05:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 11:05:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-28 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 11:05:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-03-28 11:05:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-28 11:05:58 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 11:05:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 58 Can call startListeningForAdvertisements without error
2017-03-28 11:05:58 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28(lldb) , 11:05:58 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 59 Can call stopListeningForAdvertisements without error
,# teardown
,2017-03-28 11:06:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 11:06:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 60 Should be able to call stopListeningForAdvertisements in teardown
,2017-03-28 11:06:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 61 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 11:06:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 11:06:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAd,vertisingStateUpdateNonTCP registered to native'
2017-03-28 11:06:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 11:06:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 11:06:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 11:06:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 11:06:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 11:06:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-03-28 11:06:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-28 11:06:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 11:06:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
2017-03-28 11:06:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-28 (lldb) ,11:06:05 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-03-28 11:06:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-03-28 11:06:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 11:06:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:06 - INFO thal(lldb) ,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 11:06:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ,e'
2017-03-28 11:06:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 11:06:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 11:06:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 11:06:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 11:06:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 11:06:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 11:06:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
,2017-03-28 11:06:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 66 Can call stopListeningForAdvertisements without error
2017-03-28 11:06:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:07 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
(lldb) ,2017-03-28 11:06:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 11:06:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 11:06:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-28 11:06:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 11:06:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 11:06:09 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 11:06:09 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 11:06:09 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 11:06:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 11:06:09 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 11:06:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
,2017-03-28 11:06:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 11:06:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 11:06:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 70 Can call startUpdateAdvertisingAndListening without error
2017-03-28 11:06:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03(lldb) ,-28 11:06:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-03-28 11:06:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
,ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 11:06:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:15 - INFO thaliMob(lldb) ,ile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 11:06:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-03-28 11:06:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 11:06:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 11:06:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 11:06:15 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 11:06:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 11:06:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 11:06:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,2017-03-28 11:06:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 11:06:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 11:06:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
2017-03-28 11:06:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-(lldb) ,28 11:06:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nul,l,"networkType":null}})'
(lldb) ,2017-03-28 11:06:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
(lldb) ,2017-03-28 11:06:19 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-03-28 11:06:19 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-03-28 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 11:06:19 - DEBUG thaliMobil(lldb) ,eNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:19 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopA,dvertisingAndListening in teardown
2017-03-28 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered(lldb) , ,to native'
(lldb) ,2017-03-28 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 11:06:19 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 11:06:19 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-28 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 11:06:19 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-03-28 11:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 78 Can call startUpdateAdvertisingAndListening without error
2017-03-28 11:06:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:20 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 79 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 11:06:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 11:06:21 -, DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 11:06:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# peerAvailabilityChange is called
,2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 11:06:21 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 11:06:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListeningwithout error
2017-03-28 11:06:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-28(lldb) , 11:06:21 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
,2017-03-28 11:06:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call startListeningForAdvertisements without error
(lldb) ,ok 84 peers must be an array
,ok 85 peers must not be zero-length
(lldb) ,ok 86 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 87 peerIdentifier must be a string
(lldb) ,ok 88 generation must be a number
,# teardown
(lldb) ,2017-03-28 11:06:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-03-28 11:06:24 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-03-28 11:06:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 11:06:24 - DEBUG thaliMobil(lldb) ,eNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 11:06:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 90 Should be able to call stopA,dvertisingAndListening in teardown
2017-03-28 11:06:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 11:06:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered (lldb) ,to native'
,2017-03-28 11:06:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 11:06:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 11:06:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 11:06:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 11:06:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 11:06:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can connect to a remote peer
,2017-03-28 11:06:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 11:06:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 11:06:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 91 Can call startUpdateAdvertisingAndListening without error
2017-03-28 11:06:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-2(lldb) ,8 11:06:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,,"(lldb) ,networkType":null}})'
2017-03-28 11:06:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 92 Can call startListeningForAdvertisements without error
,2017-03-28 11:06:32 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"CDB3681A-FE3C-4C8B-8DDB-D73D497E7989","generation":0}]'
(lldb) ,2017-03-28 11:06:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for CDB3681A-FE3C-4C8B-8DDB-D73D497E7989 (syncValue: baVoapIZotmgCDZwZR06t2YPr9ycJhlj)'
,2017-03-28 11:06:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
(lldb) ,2017-03-28 11:06:34 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"2EDE5185-827B-4020-9AA3-EFC1E02E0C2F","generation":0}]'
(lldb) ,Process 550 stopped
* thread #37: tid = 0x11bf83, 0x00000001871a3014 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
    frame #0: 0x00000001871a3014 libsystem_kernel.dylib`__pthread_kill + 8
libsystem_kernel.dylib`__pthread_kill:
->  0x1871a3014 <+8>:  b.lo   0x1871a302c               ; <+32>
    0x1871a3018 <+12>: stp    x29, x30, [sp, #-16]!
    0x1871a301c <+16>: mov    x29, sp
    0x1871a3020 <+20>: bl     0x1871867d0               ; cerror_nocancel
(lldb) ,* thread #37: tid = 0x11bf83, 0x00000001871a3014 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
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
    frame #10: 0x00000001000573a0 ThaliTest`-[JXcoreExtension(AppContextDelegate) context:didResolveMultiConnectWithSyncValue:error:listeningPort:] + 292
    frame #11: 0x000000010005fa10 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded, Arg[2] = Owned To Guaranteed> of ThaliTest.AppContext.(handleMultiConnectResolved in _F3DAF5A2B391CB31FC98FBDA08CABB7E) (withSyncValue : Swift.String, port : Swift.Optional<Swift.UInt16>, error : Swift.Optional<Swift.Error>) -> () + 484
    frame #12: 0x0000000100061d50 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded, Arg[1] = Owned To Guaranteed, Arg[3] = Owned To Guaranteed, Arg[4] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.(multiConnectToPeer (Swift.Array<Swift.AnyObject>, validationCompletionHandler : (Swift.Optional<__ObjC.NSError>) -> ()) -> ()).(closure #1) + 124
    frame #13: 0x0000000100059b48 ThaliTest`ThaliTest.AppContext.(multiConnectToPeer (Swift.Array<Swift.AnyObject>, validationCompletionHandler : (Swift.Optional<__ObjC.NSError>) -> ()) -> ()).(closure #1) + 44
    frame #14: 0x0000000100063614 ThaliTest`partial apply forwarder for ThaliTest.AppContext.(multiConnectToPeer (Swift.Array<Swift.AnyObject>, validationCompletionHandler : (Swift.Optional<__ObjC.NSError>) -> ()) -> ()).(closure #1) with unmangled suffix ".46" + 132
    frame #15: 0x0000000100af5450 ThaliCore`ThaliCore.BrowserManager.(connectToPeer (Swift.String, syncValue : Swift.String, completion : (Swift.String, Swift.Optional<Swift.Error>, Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #1).(closure #1) + 156
    frame #16: 0x0000000100b10944 ThaliCore`ThaliCore.BrowserRelay.(openRelay (with : (Swift.Optional<Swift.UInt16>, Swift.Optional<Swift.Error>) -> ()) -> ()).(closure #1) + 112
    frame #17: 0x0000000100aeb98c ThaliCore`ThaliCore.TCPListener.startListeningForConnections (on : Swift.UInt16, connectionAccepted : (__ObjC.GCDAsyncSocket) -> (), completion : (Swift.Optional<Swift.UInt16>, Swift.Optional<Swift.Error>) -> ()) -> () + 512
    frame #18: 0x0000000100b107ac ThaliCore`ThaliCore.BrowserRelay.openRelay (with : (Swift.Optional<Swift.UInt16>, Swift.Optional<Swift.Error>) -> ()) -> () + 304
    frame #19: 0x0000000100af523c ThaliCore`ThaliCore.BrowserManager.(connectToPeer (Swift.String, syncValue : Swift.String, completion : (Swift.String, Swift.Optional<Swift.Error>, Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #1) + 476
    frame #20: 0x0000000100af53a8 ThaliCore`partial apply forwarder for ThaliCore.BrowserManager.(connectToPeer (Swift.String, syncValue : Swift.String, completion : (Swift.String, Swift.Optional<Swift.Error>, Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #1) + 176
    frame #21: 0x0000000100b4e2d4 ThaliCore`ThaliCore.Session.(session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChange : __C.MCSessionState) -> ()).(closure #1) + 348
    frame #22: 0x0000000100b4e318 ThaliCore`reabstraction thunk helper from @callee_owned (@inout __C.MCSessionState) -> (@error @owned Swift.Error) to @callee_owned (@inout __C.MCSessionState) -> (@out (), @error @owned Swift.Error) + 36
    frame #23: 0x0000000100b486c0 ThaliCore`ThaliCore.Atomic.modify <A> (action : (inout A) throws -> A1) throws -> A1 + 136
    frame #24: 0x0000000100b4e140 ThaliCore`ThaliCore.Session.session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChange : __C.MCSessionState) -> () + 664
    frame #25: 0x0000000100b4e3d0 ThaliCore`@objc ThaliCore.Session.session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChange : __C.MCSessionState) -> () + 100
    frame #26: 0x000000019cdb5960 MultipeerConnectivity`<redacted> + 148
    frame #27: 0x000000018705e1fc libdispatch.dylib`<redacted> + 24
    frame #28: 0x000000018705e1bc libdispatch.dylib`<redacted> + 16
    frame #29: 0x000000018706c3dc libdispatch.dylib`<redacted> + 928
    frame #30: 0x00000001870619a4 libdispatch.dylib`<redacted> + 652
    frame #31: 0x000000018706e34c libdispatch.dylib`<redacted> + 572
    frame #32: 0x000000018706e0ac libdispatch.dylib`<redacted> + 124
    frame #33: 0x00000001872672a0 libsystem_pthread.dylib`_pthread_wqthread + 1288

```
