#### Test 1219585698171119_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1219585698171119/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/22E2EF17-7668-474A-8105-A6B0022DC887/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/22E2EF17-7668-474A-8105-A6B0022DC887/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1219585698171119/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/1219585698171119/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:59061"
,(lldb)     command script import "/tmp/22E2EF17-7668-474A-8105-A6B0022DC887/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
(lldb)     connect
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
,2017-05-23 11:31:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-05-23 11:31:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-23 11:31:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:31:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-23 11:31:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:31:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:31:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo(lldb) ,rrect finished
AppContextTests finished
All tests finished
All tests finished
2017-05-23 11:31:46 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
,Total number of executed tests:  13
Number of passed tests:  13
(lldb) ,Number of failed tests:  0
,(lldb) ,Number of ignored tests:  0
Total duration:  1.953242838382721
,2017-05-23 11:31:46 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
(lldb) ,2017-05-23 11:31:46 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-05-23 11:31:49 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-05-23 11:31:49 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-05-23 11:31:50 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
(lldb) ,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
(lldb) ,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
(lldb) ,2017-05-23 11:31:51 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-05-23 11:31:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-05-23 11:31:52 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
(lldb) ,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
(lldb) ,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-05-23 11:31:53 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-05-23 11:31:53 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-05-23 11:31:53 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
(lldb) ,2017-05-23 11:32:13 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-05-23 11:32:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
,# closeAll with promise
(lldb) ,2017-05-23 11:32:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-05-23 11:32:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-05-23 11:32:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-05-23 11:32:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-05-23 11:32:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-05-23 11:32:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-05-23 11:32:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
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
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
,ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
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
ok 32 fourth
ok 33 second
ok 34 secondPromise - in then
(lldb) ,ok 35 first
ok 36 firstPromise - in catch
ok 37 third
ok 38 thirdPromise - in then
ok 39 testingPromises
,# teardown
,# setup
(lldb) ,# queues handled independently
(lldb) ,ok 40 all short operations completed before the long resolves
# teardown
,# setup
(lldb) ,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
ok 42 executors is called
(lldb) ,# teardown
,# setup
(lldb) ,# exceptions in the executor are properly handled
(lldb) ,ok 43 got expected error
,# teardown
(lldb) ,# setup
,# basic
(lldb) ,ok 44 sane
,# teardown
(lldb) ,# setup
,# another
(lldb) ,ok 45 sane
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox spy
(lldb) ,2017-05-23 11:32:59 - DEBUG testTests: 'test spy method for global sinon sansbox'
(lldb) ,ok 46 test sandbox spy works correctly
,# teardown
,# setup
(lldb) ,# test sinon sansbox stub
,ok 47 test sandbox stub works correctly
(lldb) ,# teardown
(lldb) ,# setup
,# test sinon sansbox stub override
(lldb) ,ok 48 test sandbox stub works correctly
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox mock
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox restore after test end
,ok 49 test restore
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
,# teardown
(lldb) ,# setup
(lldb) ,# onPeerLost calls jxcore
(lldb) ,2017-05-23 11:33:23 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
(lldb) ,# teardown
(lldb) ,2017-05-23 11:33:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-05-23 11:33:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-23 11:33:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:33:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-23 11:33:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-23 11:33:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:33:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:33:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# onPeerDiscovered calls jxcore
(lldb) ,2017-05-23 11:33:25 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-05-23 11:33:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-23 11:33:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-05-23 11:33:26 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:33:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-05-23 11:33:26 - INFO thaliMobile: 'Filtered out networ,kChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-23 11:33:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-23 11:33:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:33:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-05-23 11:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-23 11:33:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-23 11:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 62 Can call startListeningForAdvertisements without error
,2017-05-23 11:33:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:33:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 63 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-05-23 11:33:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-05-23 11:33:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:33:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:33:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-05-23 11:33:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-05-23 11:33:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-23 11:33:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-23 11:33:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-23 11:33:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-23 11:33:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:33:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:33:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-05-23 11:33:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-23 11:33:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-05-23 11:33:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 66 Can call startListeningForAdvertisements without error
2017-05-23 11:33:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-05-23 ,11:33:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"(lldb) ,n,etworkType":null}})'
2017-05-23 11:33:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call startListeningForAdvertisements twice without error
(lldb) ,# teardown
,2017-05-23 11:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:33:56 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:33:56 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:33:56 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
2017-05-23 11:33:56 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-05-23 11:33:56 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-05-23 11:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-05-23 11:33:56 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-05-23 11:33:56 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-05-23 11:33:56 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-05-23 11:33:56 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-05-23 11:33:56 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-05-23 11:34:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 70 Can call stopListeningForAdvertisements without error
2017-05-23 11:34:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:21 - INFO thaliMobile: 'Fi(lldb) ,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-05-23 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:24 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-05-23 11:34:24 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-05-23 11:34:24 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardown
2017-05-23 11:34:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ,e'
2017-05-23 11:34:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-05-23 11:34:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-05-23 11:34:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-05-23 11:34:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-05-23 11:35:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-05-23 11:35:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-05-23 11:35:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-05-23 11:35:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-05-23 11:35:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 75 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
(lldb) ,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll, works even with a server that is not listening yet witheatNotRunning set to true'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-05-23 11:36:46 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes(lldb) , that are in the checkpoints plugin delay interval'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-05,-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGG(lldb) ,ER result: passed - enqueue and run in order'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en(lldb) ,queueAtTop'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueued function are always executed asynchronously',
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - exceptions in the executor are properly handled'
2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-05-23 11:36:46 - INFO Coordinated(lldb) ,Client: '***TEST_LOGGER result: passed - another'
,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox spy'
(lldb) ,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub'
(lldb) ,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox stub override'
,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox mock'
(lldb) ,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test sinon sansbox restore after test end'
,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
(lldb) ,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
(lldb) ,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
(lldb) ,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-05-23 11:36:46 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Can call start/stopUpdateAdvertisingAndListening, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F,49-E41E68C840E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/(lldb) ,release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-05-23 11:36:46 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
(lldb) ,2017-05-23 11:36:54 - DEBUG CoordinatedClient: 'all tests completed'
(lldb) ,2017-05-23 11:37:10 - DEBUG CoordinatedClient: 'test client disconnected'
2017-05-23 11:37:10 - DEBUG CoordinatedClient: 'test client failed'
(lldb) ,2017-05-23 11:37:10 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: TimeoutError: timeout exceeded, event: 'teardown_Can call start/stopUpdateAdvertisingAndListening_finished', test: 'Can call start/stopUpdateAdvertisingAndListening'', stack: ',CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/lib/CoordinatedClient.js:291:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/A1ADBCF2-FE(lldb) ,5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/node_modules/socket.io-clien,t/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Ap(lldb) ,p,lication/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/private/var/containers/Bundle/Application/A1ADBCF2-FE5A-492B-9F49-E41E68C840E2/ThaliTest.app/www/jxcore/node_modules/(lldb) ,component-emitter/index.js:131:7''
2017-05-23 11:37:10 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
