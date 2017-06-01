#### Test 122449695f36eb0f_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/122449695f36eb0f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/76338608-157B-4C8C-BE1B-DE91FB11ECCC/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/76338608-157B-4C8C-BE1B-DE91FB11ECCC/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/122449695f36eb0f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/122449695f36eb0f/build_ios/ThaliTest.app' (arm64).
,(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:62895"
,(lldb)     command script import "/tmp/76338608-157B-4C8C-BE1B-DE91FB11ECCC/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,Initializing JXcore engine
JXcore engine is ready
(lldb) ,Starting JXcore engine
,Platform ios
,Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
,JXcore engine is started
(lldb) ,2017-06-01 14:26:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-01 14:26:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-01 14:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:26:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:26:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:26:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:26:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
(lldb) ,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
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
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-06-01 14:26:32 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
(lldb) ,Total duration:  1.686048984527588
,2017-06-01 14:26:32 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
(lldb) ,2017-06-01 14:26:32 - WARN testUtils: 'myNameCallback not set!'
,2017-06-01 14:26:36 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-01 14:26:36 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-01 14:26:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-01 14:26:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-01 14:26:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-01 14:26:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-01 14:26:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-06-01 14:26:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-06-01 14:26:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-01 14:26:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-01 14:26:37 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-06-01 14:26:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-06-01 14:26:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-06-01 14:26:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-01 14:26:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-01 14:26:38 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-06-01 14:26:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-01 14:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-01 14:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-06-01 14:26:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-06-01 14:26:40 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-06-01 14:26:40 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-06-01 14:26:40 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-01 14:26:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-06-01 14:27:11 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-06-01 14:27:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-06-01 14:27:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
,2017-06-01 14:27:57 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
(lldb) ,# teardown
,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-06-01 14:28:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-06-01 14:28:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-06-01 14:28:45 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
(lldb) ,ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
,ok 13 should be equal
(lldb) ,ok 14 should be equal
,# teardown
(lldb) ,# setup
,# enqueue and run in order
(lldb) ,ok 15 firstPromise setTimeout
ok 16 firstPromise result
ok 17 firstPromise testValue
(lldb) ,ok 18 secondPromise setTimeout
(lldb) ,ok 19 secondPromise result
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
ok 32 fourth
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
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox spy
,2017-06-01 14:30:28 - DEBUG testTests: 'test spy method for global sinon sansbox'
ok 46 test sandbox spy works correctly
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
,# teardown
(lldb) ,# setup
,# test sinon sansbox restore after test end
(lldb) ,ok 49 test restore
,# teardown
(lldb) ,# setup
(lldb) ,# can pass data in setup
,ok 50 test participant has uuid
ok 51 participant data matches
(lldb) ,ok 52 test participant has uuid
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
(lldb) ,# onPeerLost calls jxcore
(lldb) ,2017-06-01 14:32:36 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:32:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:32:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# onPeerDiscovered calls jxcore
,2017-06-01 14:32:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
(lldb) ,# teardown
,2017-06-01 14:32:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
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
2017-06-01 14:32:43 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:32:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
2017-06-01 14:32:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01, 14:32:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 63 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-06-01 14:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-01 14:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 64 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-01 14:33:01 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-01 14:33:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 65 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-01 14:33:01 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-01 14:33:01 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-01 14:33:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:33:01 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:33:01 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:33:01 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:33:01 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:33:01 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
,2017-06-01 14:33:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-01 14:33:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:33:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 66 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-01 14:33:27 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-01 14:33:27 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
,2017-06-01 14:33:27 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:33:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:33:28 - INFO thal(lldb) ,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ,e'
2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-01 14:33:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:33:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-06-01 14:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:33:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 70 Can call stopListeningForAdvertisements without error
2017-06-01 14:33:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:33:51 - INFO thaliMobile: 'Fi(lldb) ,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 71 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-06-01 14:34:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-01 14:34:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:34:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:34:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardow,n
2017-06-01 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-01 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:34:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-01 14:34:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-01 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:34:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:34:28 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:34:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-01 14:34:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:34:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:34:28 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardown
2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:34:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:34:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-06-01 14:34:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-06-01 14:34:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-01 14:34:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-06-01 14:34:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:34:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:34:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
(lldb) ,# teardown
,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:34:45 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:34:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 80 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-06-01 14:34:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,b(lldb) ,ilityChanged registered to native'
2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:34:45 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:34:45 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-06-01 14:34:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-01 14:34:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Can call startUpdateAdvertisingAndListening without error
2017-06-01 14:34:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStat,eUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:34:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 83 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-06-01 14:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-01 14:35:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:35:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
2017-06-01 14:35:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:35:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAd,vertisingStateUpdateNonTCP registered to native'
2017-06-01 14:35:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-01 14:35:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-01 14:35:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-01 14:35:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-01 14:35:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-01 14:35:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# peerAvailabilityChange is called
,2017-06-01 14:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:35:04 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
2017-06-01 14:35:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-01(lldb) , 14:35:04 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-06-01 14:35:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 87 Can call startListeningForAdvertisements without error
(lldb) ,ok 88 peers must be an array
ok 89 peers must not be zero-length
ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
ok 91 peerIdentifier must be a string
ok 92 generation must be a number
(lldb) ,# teardown
,2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:35:06 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:35:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 93 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-06-01 14:35:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,bilityChanged registered to native'
2017-06-01 14:35:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
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
(lldb) ,2017-06-01 14:35:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-01 14:35:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di(lldb) ,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:35:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 96 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-01 14:35:14 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"9E46E725-3ABE-4C33-A0A3-1F503737E710","generation":0}]'
2017-06-01 14:35:14 - DEBUG thaliMobileNativeTestUtils: 'Issui(lldb) ,ng multiConnect for 9E46E725-3ABE-4C33-A0A3-1F503737E710 (syncValue: lw0wQZ3IyfORcJTkRUG58VAJH4xqYSB6)'
2017-06-01 14:35:14 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,2017-06-01 14:35:15 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"ACB251AD-2F01-4226-AE25-91E62AFB2CC8","generation":0}]'
(lldb) ,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
(lldb) ,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
,2017-06-01 14:35:17 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"lw0wQZ3IyfORcJTkRUG58VAJH4xqYSB6","error":null,"portNumber":50648}'
(lldb) ,2017-06-01 14:35:17 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'lw0wQZ3IyfORcJTkRUG58VAJH4xqYSB6', error: 'null', listeningPort: '50648''
,2017-06-01 14:35:17 - INFO testThaliMobileNative: ''
(lldb) ,ok 97 Must have listeningPort
,ok 98 listeningPort must be a number
(lldb) ,ok 99 listening port should not be 0
,# teardown
(lldb) ,2017-06-01 14:35:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:35:18 - INFO t,haliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}(lldb) ,})'
2017-06-01 14:35:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopListeningForAdvertisements in teardown
2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'discoveryA,dvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:35:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopAdvertisingAndListening in (lldb) ,teardown
2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-01 14:35:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:35:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can shift data
(lldb) ,2017-06-01 14:35:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:35:20 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:35:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
(lldb) ,ok 102 Can call startUpdateAdvertisingAndListening without error
2017-06-01 14:35:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-01 14:35:20 - INFO thaliMobile: 'Rec,eived state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 1(lldb) ,4:35:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 103 Can call startListeningForAdvertisements without error
,2017-06-01 14:35:22 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 20C0948C-4E4C-49F5-A816-1017AF1D4213 (syncValue: 166EGDmYzRjZK3DwYKqdQQRUOiIwzwU0)'
2017-06-01 14:35:22 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
(lldb) ,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
(lldb) ,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
,[iOS NATIVE]: [Session]: session(_:didReceiveCertificate:fromPeer:certificateHandler:)
(lldb) ,2017-06-01 14:35:24 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
,2017-06-01 14:35:24 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
(lldb) ,2017-06-01 14:35:24 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
,2017-06-01 14:35:24 - DEBUG testThaliMobileNative: 'Server data flushed'
(lldb) ,2017-06-01 14:35:24 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"166EGDmYzRjZK3DwYKqdQQRUOiIwzwU0","error":null,"portNumber":50653}'
,2017-06-01 14:35:24 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: '166EGDmYzRjZK3DwYKqdQQRUOiIwzwU0', error: 'null', listeningPort: '50653''
(lldb) ,Connecting to the localhost:50653
,Connected to the localhost:50653
(lldb) ,2017-06-01 14:35:24 - DEBUG testThaliMobileNative: 'Client sends data (20 bytes):'
,2017-06-01 14:35:24 - DEBUG testThaliMobileNative: 'Client data flushed'
(lldb) ,ok 104 got the same data back
,# teardown
(lldb) ,2017-06-01 14:35:25 - DEBUG testThaliMobileNative: 'Server received (20 bytes):'
2017-06-01 14:35:25 - DEBUG testThaliMobileNative: 'Server received all data: small amount of data'
2017-06-01 14:35:25 - DEBUG testThaliMobileNative: 'Server sends data back to client (20 bytes):'
2017-06-01 14:35:25 - DEBUG testThaliMobileNative: 'Server data flushed'
(lldb) ,2017-06-01 14:35:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-06-01 14:35:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-06-01 14:35:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 105 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-01 14:35:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-01 14:35:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-01 14:35:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
(lldb) ,# Can shift data via parallel connections
,2017-06-01 14:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-01 14:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-01 14:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
(lldb) ,ok 107 Can call startUpdateAdvertisingAndListening without error
,2017-06-01 14:35:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
(lldb) ,2017-06-01 14:35:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-01 14:35:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Can call startListeningForAdvertisements without error
,2017-06-01 14:35:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 20C0948C-4E4C-49F5-A816-1017AF1D4213 (syncValue: K60O5W60SzaFKSzN3CYh1PIPNOiv8brv)'
(lldb) ,2017-06-01 14:35:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,2017-06-01 14:35:27 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"K60O5W60SzaFKSzN3CYh1PIPNOiv8brv","error":null,"portNumber":50653}'
(lldb) ,2017-06-01 14:35:27 - DEBUG thaliMobileNativeTestUtils: 'Got multiConnectResolved -syncValue: 'K60O5W60SzaFKSzN3CYh1PIPNOiv8brv', error: 'null', listeningPort: '50653''
,Connecting to the localhost:50653
,Connecting to the localhost:50653
(lldb) ,Connecting to the localhost:50653
,Connected to the localhost:50653
(lldb) ,Connected to the localhost:50653
,Connected to the localhost:50653
(lldb) ,ok 109 correct string length
2017-06-01 14:35:27 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
(lldb) ,ok 110 correct string length
,2017-06-01 14:35:27 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
(lldb) ,ok 111 correct string length
,2017-06-01 14:35:27 - DEBUG testThaliMobileNative: 'Client sends data (16384 bytes):'
(lldb) ,2017-06-01 14:35:27 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-06-01 14:35:27 - DEBUG testThaliMobileNative: 'Client data flushed'
2017-06-01 14:35:27 - DEBUG testThaliMobileNative: 'Client data flushed'
,2017-06-01 14:38:28 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-06-01 14:38:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F(lldb) ,6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:38:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:38:33 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F(lldb) ,6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:38:33 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-01 14:38:43 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F(lldb) ,6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:38:43 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:38:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F(lldb) ,6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:38:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:39:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F(lldb) ,6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-06-01 14:39:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-06-01 14:39:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F(lldb) ,6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:39:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-4,5F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/nod(lldb) ,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var,/containers/Bundle/Application/6EB7D7CC-2E16-45F6-AC98-E318D6BF547A/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-06-01 14:39:50 - ERROR CoordinatedClient: 'connect_error error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-01 14:39:50 - DEBUG CoordinatedClient: 'test client failed'
2017-06-01 14:39:50 - ERROR CoordinatedClient: 'reconnect_er(lldb) ,ror error: 'timeout', description: 'undefined', stack: 'undefined''
2017-06-01 14:39:50 - DEBUG CoordinatedClient: 'test client failed'
,2017-06-01 14:39:50 - DEBUG CoordinatedClient: '20000'
2017-06-01 14:39:50 - ERROR CoordinatedThaliTape: 'tests failed, error: 'timeout', stack: 'undefined''
2017-06-01 14:39:50 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
(lldb) 
```
