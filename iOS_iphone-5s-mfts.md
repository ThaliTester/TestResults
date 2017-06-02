#### Test 113351851cf2de5f_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/113351851cf2de5f/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/8BDB2ABB-6D0F-43B9-A16C-73BBD108D5B4/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/8BDB2ABB-6D0F-43B9-A16C-73BBD108D5B4/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/10.2.1 (14D27)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/113351851cf2de5f/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/113351851cf2de5f/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:64883"
,(lldb)     command script import "/tmp/8BDB2ABB-6D0F-43B9-A16C-73BBD108D5B4/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
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
,2017-06-02 12:56:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 12:56:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 12:56:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 12:56:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 12:56:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 12:56:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 12:56:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
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
(lldb) ,2017-06-02 12:56:57 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  1.55178302526474
(lldb) ,2017-06-02 12:56:58 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-06-02 12:56:58 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-06-02 12:57:01 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-06-02 12:57:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-06-02 12:57:01 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-06-02 12:57:02 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-06-02 12:57:03 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-06-02 12:57:04 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testHttp.js'
(lldb) ,2017-06-02 12:57:05 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-06-02 12:57:05 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-06-02 12:57:05 - INFO CoordinatedClient: 'Connecting to coordination server on http://192.168.1.150:3000/'
(lldb) ,2017-06-02 12:57:06 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-06-02 12:57:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 1 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-06-02 12:57:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-06-02 12:57:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
,2017-06-02 12:57:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
,2017-06-02 12:58:22 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
(lldb) ,# teardown
(lldb) ,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-06-02 12:58:49 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
,2017-06-02 12:59:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
(lldb) ,# teardown
,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-06-02 12:59:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
(lldb) ,ok 4 should be equal
(lldb) ,ok 5 should be equal
,ok 6 should be equal
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
(lldb) ,ok 11 should be equal
ok 12 should be equal
ok 13 should be equal
ok 14 should be equal
,# teardown
,# setup
(lldb) ,# enqueue and run in order
(lldb) ,ok 15 firstPromise setTimeout
,ok 16 firstPromise result
(lldb) ,ok 17 firstPromise testValue
,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
(lldb) ,# teardown
,# setup
(lldb) ,# enqueueAtTop and run backwards
(lldb) ,ok 24 thirdPromise - first to run
ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
(lldb) ,ok 30 testing promises
,# teardown
(lldb) ,# setup
,# mix enqueue and enqueueAtTop
(lldb) ,ok 31 fourth
ok 32 fourth
ok 33 second
,ok 34 secondPromise - in then
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
,# enqueued function are always executed asynchronously
(lldb) ,ok 41 executor is not called here
ok 42 executors is called
,# teardown
(lldb) ,# setup
(lldb) ,# exceptions in the executor are properly handled
(lldb) ,ok 43 got expected error
(lldb) ,# teardown
,# setup
(lldb) ,# basic
(lldb) ,ok 44 sane
(lldb) ,# teardown
(lldb) ,# setup
,# another
(lldb) ,ok 45 sane
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox spy
,2017-06-02 13:04:00 - DEBUG testTests: 'test spy method for global sinon sansbox'
(lldb) ,ok 46 test sandbox spy works correctly
,# teardown
(lldb) ,# setup
,# test sinon sansbox stub
(lldb) ,ok 47 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub override
(lldb) ,ok 48 test sandbox stub works correctly
,# teardown
(lldb) ,# setup
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
(lldb) ,ok 60 throws if usn has invalid generation
ok 61 correctly stringifies peer
,# teardown
(lldb) ,# setup
,# onPeerLost calls jxcore
(lldb) ,2017-06-02 13:06:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-06-02 13:06:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:06:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:06:47 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:06:47 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:06:47 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:06:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:06:47 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:06:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# onPeerDiscovered calls jxcore
(lldb) ,2017-06-02 13:06:47 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-06-02 13:07:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:07:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:07:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:07:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:07:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:07:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:07:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:07:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-06-02 13:07:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:07:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:07:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
(lldb) ,ok 62 Can call startListeningForAdvertisements without error
2017-06-02 13:07:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:07:31 - INFO thaliMobile: 'Filte,red out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 63 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-06-02 13:07:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:07:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:07:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:07:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-02 13:07:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:07:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:07:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:07:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:07:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:07:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:07:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:07:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-02 13:08:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 66 Can call startListeningForAdvertisements without error
,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:08:00 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
(lldb) ,ok 67 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 68 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:00 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:00 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:00 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
,2017-06-02 13:08:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 70 Can call stopListeningForAdvertisements without error
2017-06-02 13:08:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:03 - INFO thaliMobile: 'Fi(lldb) ,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 71 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-06-02 13:08:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-02 13:08:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:08:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:08:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:05 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-06-02 13:08:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:08:09 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 74 Can call startUpdateAdvertisingAndListening without error
2017-06-02 13:08:09 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06(lldb) ,-02 13:08:09 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 75 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:08:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 78 Can call startUpdateAdvertisingAndListening without error
2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-(lldb) ,02 13:08:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nul,l(lldb) ,,"networkType":null}})'
2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 79 Can call startUpdateAdvertisingAndListening twice without error
(lldb) ,# teardown
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-06-02 13:08:25 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 80 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
(lldb) ,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 82 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-06-02 13:08:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:08:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 83 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 84 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:26 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 85 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:26 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:08:26 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# peerAvailabilityChange is called
(lldb) ,2017-06-02 13:08:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:08:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Can call startUpdateAdvertisingAndListeningwithout error
(lldb) ,2017-06-02 13:08:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-02 13:08:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat(lldb) ,eUpdate (was in stopped state).'
ok 87 Can call startListeningForAdvertisements without error
,ok 88 peers must be an array
ok 89 peers must not be zero-length
(lldb) ,ok 90 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 91 peerIdentifier must be a string
(lldb) ,ok 92 generation must be a number
,# teardown
(lldb) ,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-06-02 13:08:32 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:08:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 93 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:08:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 94 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:08:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
(lldb) ,2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 95 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 96 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
(lldb) ,2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 97 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 98 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:33 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can shift data via parallel connections
,2017-06-02 13:08:33 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data via parallel connections''
(lldb) ,# teardown
,2017-06-02 13:08:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:08:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 99 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:08:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:08:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 100 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:08:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailab(lldb) ,ilityChanged registered to native'
2017-06-02 13:08:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:08:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to ,native'
(lldb) ,2017-06-02 13:08:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:08:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:08:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:08:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:08:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can shift data securely
(lldb) ,2017-06-02 13:08:58 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift data securely''
,# teardown
(lldb) ,2017-06-02 13:09:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 101 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-02 13:09:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:09:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 102 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-02 13:09:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:09:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:09:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:09:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:09:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:09:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:09:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can shift large amounts of data
(lldb) ,2017-06-02 13:09:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Can shift large amounts of data''
,# teardown
(lldb) ,2017-06-02 13:09:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:22 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 103 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:22 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:22 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 104 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:09:22 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
,2017-06-02 13:09:22 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:09:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:22 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:09:22 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:09:22 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:09:22 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:09:22 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# We do not emit peerAvailabilityChanged events until one of the start methods is called
(lldb) ,2017-06-02 13:09:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:09:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:09:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 105 We should start listening fine
2017-06-02 13:09:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-06-02 13:09:26 - INFO thaliMob(lldb) ,ile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
20,1(lldb) ,7-06-02 13:09:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 106 We should start updating fine
,# teardown
(lldb) ,2017-06-02 13:09:28 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"11404973-4491-4482-B0BB-E5B96B33DFEB","generation":0}]'
2017-06-02 13:09:28 - DEBUG thaliMobileNativeW(lldb) ,rapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"11404973-4491-4482-B0BB-E5B96B33DFEB","generation":0}'
2017-06-02 13:09:28 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent du,e to not being in started state'
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:09:35 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:09:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 107 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-06-02 13:09:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 108 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvai(lldb) ,labilityChanged registered to native'
,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:09:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Test updating advertising and parallel data transfer
(lldb) ,2017-06-02 13:09:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Test updating advertising and parallel data transfer''
,# teardown
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 109 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:35 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 110 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat,ive'
2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:09:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:09:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# discoveryAdvertisingStateUpdateNonTCP is called
(lldb) ,ok 111 discoveryActive should be false
,ok 112 advertisingActive should be true
(lldb) ,ok 113 discoveryActive should be false
,ok 114 advertisingActive should be true
(lldb) ,ok 115 discoveryActive should be false
,ok 116 advertisingActive should be true
ok 117 discoveryActive should be false
(lldb) ,ok 118 advertisingActive should be true
ok 119 Can call stopAdvertisingAndListening without error
,2017-06-02 13:09:35 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/lib/Coordinated(lldb) ,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-,8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat(lldb) ,e/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":8,"ok":true,"name":"Can call stopAdvertisingAndListening without error","operator":"notOk","actu,al":null,"expected":false}''
(lldb) ,ok 120 Can call stopListeningForAdvertisements without error
,2017-06-02 13:09:35 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/lib/Coordinated(lldb) ,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-,8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat(lldb) ,e/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":9,"ok":true,"name":"Can call stopListeningForAdvertisements without error","operator":"notOk","a,ctual":null,"expected":false}''
(lldb) ,ok 121 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-06-02 13:09:35 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/lib/Coordinated,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-(lldb) ,8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat,e/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":10,"ok":true,"name":"Can call startUpdateAdvertisingAndListening without error","operator":"notO(lldb) ,k","actual":null,"expected":false}''
,ok 122 Can call startListeningForAdvertisements without error
(lldb) ,2017-06-02 13:09:36 - ERROR CoordinatedClient: 'unexpected result, error: 'Error', stack: 'CoordinatedClient.prototype.unexpectedResult@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/lib/Coordinated,Client.js:585:13
emit@events.js:98:1
bound@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
assert@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-(lldb) ,8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:245:5
bound@/private/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:62:28
Test.prototype.notok@/privat,e/var/containers/Bundle/Application/8F1CBF6F-A7F9-4EA9-8B1D-68FBEE7024BD/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:309:1', original result: '{"id":11,"ok":true,"name":"Can call startListeningForAdvertisements without error","operator":"notOk",,"actual":null,"expected":false}''
(lldb) ,# teardown
,ok 123 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,ok 124 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdver,tisingStateUpdateNonTCP registered to native'
2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:09:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:09:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# cannot call connect when start listening for advertisements is not active
(lldb) ,2017-06-02 13:09:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'cannot call connect when start listening for advertisements is not active''
,# teardown
(lldb) ,2017-06-02 13:09:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 125 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 126 Should be able to call stopAdvertisingAndListening in teard(lldb) ,own
,# setup
(lldb) ,# Get error when trying to double connect to a peer on Android
,2017-06-02 13:09:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get error when trying to double connect to a peer on Android''
(lldb) ,# teardown
,2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 127 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:40 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 128 Should be able to call stopAdvertisingAndListening in teardown
,# setup
(lldb) ,# #startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection
,2017-06-02 13:09:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending remote peers connection kills the local connection''
(lldb) ,# teardown
,2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 129 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:40 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 130 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,# setup
,# #startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection
(lldb) ,2017-06-02 13:09:40 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying remote peers connection kills the local connection''
,# teardown
(lldb) ,2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:09:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 131 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 132 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,# setup
(lldb) ,# #startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer
,2017-06-02 13:09:41 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - destroying the local connection kills the connection to the remote peer''
(lldb) ,# teardown
(lldb) ,2017-06-02 13:09:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 133 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:45 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:45 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 134 Should be able to call stopAdvertisingAndListening in teard(lldb) ,own
,# setup
(lldb) ,# #startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer
,2017-06-02 13:09:45 - DEBUG CoordinatedClient: 'test was skipped, name: '#startUpdateAdvertisingAndListening - ending the local connection kills the connection to the remote peer''
(lldb) ,# teardown
,2017-06-02 13:09:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 135 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:46 - INFO tha(lldb) ,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 136 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,# setup
,# cannot call multiConnect when start listening for advertisements is not active
(lldb) ,ok 137 Got null as expected
2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"PTmqEJ1B95S42DBBGBbFxK2SmAfpWERe","error":"startListeningForAdvertisements is not active","portNumber":null}'
ok 138 Should only get called after multiConnect returned
ok 139 SyncValue matches
ok 140 Got right error
ok 141 listeningPort is null
(lldb) ,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"43e0fc9a-d1e4-4474-89b8-b57f4dd88ace","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-06-02 13:09:49 - DEBUG thaliMobil(lldb) ,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"43e0fc9a-d1e4-4474-89b8-b57f4dd88ac,e","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
(lldb) ,# teardown
,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 142 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:09:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 143 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:09:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:09:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
(lldb) ,# cannot call multiConnect with illegal peerID
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 144 No error on starting
,ok 145 Got null as expected
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"oxJniaxN2WLxBMvBfo0UzcK1AGBHoX4t","error":"Illegal peerID","portNumber":null}'
ok 146 Should only get called after multiConnect returned
ok 147 SyncValue matches
,ok 148 Got right error
ok 149 listeningPort is null
(lldb) ,# teardown
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"11404973-4491-4482-B0BB-E5B96B33DFEB","generation":0}]'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"11404973-4491-4482-B0BB-E5B96B33DFEB","generation":0}'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 150 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 151 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# multiConnect properly fails on legal but non-existent peerID
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:09:50 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:09:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 152 No error on starting
,ok 153 Got null as expected
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'multiConnectResolved: {"syncValue":"9ioI5Phx93Vzyj8woaunMATuZc1sC0nh","error":"Connection could not be established","portNumber":null}'
ok 154 Should only get called after multiConnect returned
ok 155 SyncValue matches
(lldb) ,ok 156 Got right error
ok 157 listeningPort is null
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"cfb49655-d62a-4375-b710-f703648a23bb","peerAvailable":false,"portNumber":null,"recreated":true}'
2017-06-02 13:09:50 - DEBUG thaliMobil,eNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"cfb49655-d62a-4375-b710-f703648a23b(lldb) ,b","peerAvailable":true,"portNumber":null,"recreated":true}'
2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,# teardown
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Received peerAvailabilityChanged event from native layer [{"peerAvailable":true,"peerIdentifier":"11404973-4491-4482-B0BB-E5B96B33DFEB","generation":0}]'
,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerAvailable":true,"peerIdentifier":"11404973-4491-4482-B0BB-E5B96B33DFEB","generation":0}'
(lldb) ,2017-06-02 13:09:50 - DEBUG thaliMobileNativeWrapper: 'Filtered out nonTCPPeerAvailabilityChangedEvent due to not being in started state'
,2017-06-02 13:09:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 158 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:09:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:09:52 - INFO tha,liMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 159 Should be able to call stopAdvertisingAndListening in teardown
2017-06-02 13:09:52 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nat(lldb) ,ive'
,2017-06-02 13:09:52 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:09:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:09:52 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:09:52 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:09:52 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:09:52 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:09:52 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# cannot call multiConnect with invalid syncValue
(lldb) ,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-06-02 13:10:14 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:10:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
(lldb) ,ok 160 No error on starting
,ok 161 Got right error
(lldb) ,# teardown
,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:10:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 162 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:10:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 163 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:10:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:10:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# disconnect doesn't fail on bad peer id
(lldb) ,ok 164 No error
(lldb) ,# teardown
,2017-06-02 13:10:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:10:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 165 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:10:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert(lldb) ,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:10:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 166 Should be able to call stopAdvertisingAndListening in teard,own
2017-06-02 13:10:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:10:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:10:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:10:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:10:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:10:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:10:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:10:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# disconnect doesn't fail on plausible but bogus peer ID
(lldb) ,ok 167 No error
,# teardown
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 168 Should be able to call stopListeningForAdvertisements in teardown
2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvert,isingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 169 Should be able to call stopAdvertisingAndListening in teard(lldb) ,own
2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Get same port when trying to connect multiple times on iOS
,2017-06-02 13:11:02 - DEBUG CoordinatedClient: 'test was skipped, name: 'Get same port when trying to connect multiple times on iOS''
(lldb) ,# teardown
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 170 Should be able to call stopListeningForAdvertisements in teardown
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:11:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 171 Should be able to call stopAdvertisingAndListening in teardown
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:11:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
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
,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:11:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:11:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# update peer discovery 1
,2017-06-02 13:11:03 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 1''
(lldb) ,# teardown
,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-02 13:11:07 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:11:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# update peer discovery 2
(lldb) ,2017-06-02 13:11:10 - DEBUG CoordinatedClient: 'test was skipped, name: 'update peer discovery 2''
,# teardown
(lldb) ,2017-06-02 13:11:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:11:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:11:24 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:11:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:11:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:11:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:11:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:11:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# check latest peer discovery
(lldb) ,2017-06-02 13:11:32 - DEBUG CoordinatedClient: 'test was skipped, name: 'check latest peer discovery''
,# teardown
(lldb) ,2017-06-02 13:11:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:11:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:11:51 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:11:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:11:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:11:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:11:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:11:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Set up for no peer discovery test
,2017-06-02 13:11:52 - DEBUG CoordinatedClient: 'test was skipped, name: 'Set up for no peer discovery test''
(lldb) ,# teardown
(lldb) ,2017-06-02 13:12:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:12:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:12:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:12:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:12:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:12:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:12:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:12:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# no peer discovery
(lldb) ,2017-06-02 13:12:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'no peer discovery''
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
2017-06-02 13:12:20 - DEBUG createNativeListener: 'listening 50764'
ok 172 Should throw
(lldb) ,# teardown
,2017-06-02 13:12:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:12:20 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# emits incomingConnectionState
(lldb) ,2017-06-02 13:12:21 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:12:21 - DEBUG createNativeListener: 'listening 50766'
,2017-06-02 13:12:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-02 13:12:21 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 173 initial connection state should be CONNECTED
,2017-06-02 13:12:21 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 174 final connection state should be DISCONNECTED
(lldb) ,# teardown
,2017-06-02 13:12:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:12:22 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# emits routerPortConnectionFailed
(lldb) ,2017-06-02 13:12:44 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:12:44 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:12:44 - DEBUG createNativeListener: 'listening 50769'
,2017-06-02 13:12:44 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
(lldb) ,2017-06-02 13:12:44 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-02 13:12:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,2017-06-02 13:12:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
,ok 175 tried to connect to right port
(lldb) ,ok 176 failed due to refused connection
,ok 177 routerPortConnectionFailed is emitted
(lldb) ,# teardown
,2017-06-02 13:12:45 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,2017-06-02 13:12:45 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-02 13:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Native Server - close'
2017-06-02 13:12:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2017-06-02 13:12:49 - DEBUG createNativeListener: 'incoming (lldb) ,- incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
,(lldb) ,# native server connections all up
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'listening 50773'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
,ok 178 Send/recvd #1 should be equal length
(lldb) ,ok 179 Send/recvd #1 should be same
,ok 180 Send/recvd #2 should be equal length
(lldb) ,ok 181 Send/recvd #2 should be same
,ok 182 Should be exactly 2 client sockets
,# teardown
(lldb) ,2017-06-02 13:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:12:49 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Native Server - close'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# setup
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# native server - closing incoming stream cleans outgoing socket
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Creating Native Server'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'listening 50778'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,ok 183 socket shouldn't close until after stream
(lldb) ,ok 184 incoming remains open
,# teardown
(lldb) ,2017-06-02 13:12:49 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,2017-06-02 13:12:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:12:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:12:50 - DEBUG createNativeListener: 'Native Server - close'
2017-06-02 13:12:50 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <(lldb) ,-> Mux - 0 - close'
2017-06-02 13:12:50 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
(lldb) ,# native server - closing incoming connection cleans outgoing socket
,2017-06-02 13:13:03 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:13:03 - DEBUG createNativeListener: 'listening 50783'
,2017-06-02 13:13:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
(lldb) ,2017-06-02 13:13:03 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 185 we should not have gotten an error
(lldb) ,2017-06-02 13:13:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-02 13:13:03 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-02 13:13:03 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 186 socket shouldn't close until after incoming
(lldb) ,ok 187 incoming is cleaned up
,# teardown
(lldb) ,2017-06-02 13:13:03 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,2017-06-02 13:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:13:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:13:04 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# native server - closing outgoing socket cleans associated mux stream
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'Creating Native Server'
,2017-06-02 13:13:18 - DEBUG createNativeListener: 'listening 50787'
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-02 13:13:18 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-02 13:13:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-02 13:13:18 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,ok 188 stream was closed
,ok 189 incoming should survive
(lldb) ,ok 190 mux should have no streams
,# teardown
(lldb) ,2017-06-02 13:13:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:13:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'Native Server - close'
,2017-06-02 13:13:18 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-02 13:13:18 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,# setup
(lldb) ,# native server - closing the whole server cleans everything up
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:13:19 - DEBUG createNativeListener: 'listening 50791'
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,ok 191 we should not have gotten an error
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
(lldb) ,ok 192 Buffers are identical
,2017-06-02 13:13:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:13:19 - DEBUG createNativeListener: 'Native Server - close'
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-02 13:13:19 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 193 native server is nulled out
(lldb) ,ok 194 native server should be closed
(lldb) ,ok 195 incoming has been removed
,ok 196 Incoming should be done
(lldb) ,ok 197 The mux object should be closed
(lldb) ,ok 198 The mux stream should be closed
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,# teardown
,2017-06-02 13:13:19 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,2017-06-02 13:13:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,# setup
(lldb) ,# native server - we can get a ton of connections and data through and still clean up the server completely
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:13:24 - DEBUG createNativeListener: 'listening 50795'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:24 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
,2017-06-02 13:13:24 - DEBUG createNativeListener: 'Native Server - Creating Mux'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
(lldb) ,2017-06-02 13:13:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,ok 199 native server is nulled out
(lldb) ,ok 200 native server should be closed
,ok 201 incoming has been removed
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
(lldb) ,2017-06-02 13:13:25 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
(lldb) ,2017-06-02 13:13:27 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# setup
,# native server - simulate mux failure, make sure everything is cleaned up
(lldb) ,2017-06-02 13:13:57 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:13:57 - DEBUG createNativeListener: 'listening 50848'
,2017-06-02 13:13:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
(lldb) ,2017-06-02 13:13:57 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 202 we should not have gotten an error
(lldb) ,2017-06-02 13:13:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 203 Buffers are identical
(lldb) ,2017-06-02 13:13:57 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
,2017-06-02 13:13:57 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,2017-06-02 13:13:57 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,ok 204 server should be fine
(lldb) ,ok 205 server should be open
,ok 206 incoming has been removed
(lldb) ,ok 207 The mux object should be closed
,ok 208 The mux stream should be closed
(lldb) ,2017-06-02 13:13:57 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
,# teardown
(lldb) ,2017-06-02 13:13:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:13:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:13:59 - DEBUG createNativeListener: 'Native Server - close'
(lldb) ,# setup
,# native server - timing out the incoming connection cleans everything up
(lldb) ,2017-06-02 13:14:16 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:14:16 - DEBUG createNativeListener: 'listening 50852'
(lldb) ,2017-06-02 13:14:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-02 13:14:16 - DEBUG createNativeListener: 'Native Server - Creating Mux'
,ok 209 we should not have gotten an error
(lldb) ,2017-06-02 13:14:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
,ok 210 Buffers are identical
(lldb) ,2017-06-02 13:14:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
,2017-06-02 13:14:16 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
(lldb) ,2017-06-02 13:14:16 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
,2017-06-02 13:14:16 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 211 server should be fine
,ok 212 server should be open
,ok 213 incoming has been removed
(lldb) ,ok 214 The mux object should be closed
,ok 215 The mux stream should be closed
(lldb) ,# teardown
,2017-06-02 13:14:16 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
(lldb) ,2017-06-02 13:14:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:14:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2017-06-02 13:14:17 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# can create servers manager
,ok 216 serversManager must not be null
ok 217 serversManager must be an object
(lldb) ,# teardown
,# setup
(lldb) ,# calling stop without start causes error
(lldb) ,ok 218 We need to call start first
,# teardown
(lldb) ,# setup
(lldb) ,# can start/stop servers manager
,2017-06-02 13:15:15 - DEBUG createNativeListener: 'Creating Native Server'
(lldb) ,2017-06-02 13:15:15 - DEBUG createNativeListener: 'listening 50858'
,ok 219 port must be in range
(lldb) ,# teardown
,2017-06-02 13:15:15 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:15:15 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# starting twice resolves with listening port
(lldb) ,2017-06-02 13:15:19 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:15:19 - DEBUG createNativeListener: 'listening 50859'
ok 220 second start should return same port
(lldb) ,# teardown
,2017-06-02 13:15:48 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:15:48 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# terminateIncomingConnection will terminate a connection
,2017-06-02 13:15:55 - DEBUG createNativeListener: 'Creating Native Server'
2017-06-02 13:15:55 - DEBUG createNativeListener: 'listening 50862'
(lldb) ,2017-06-02 13:15:55 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2017-06-02 13:15:55 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 221 we should be connected
2017-06-02 13:15:55 - DEB,UG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
(lldb) ,ok 222 now we are disconnected
,2017-06-02 13:15:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,# teardown
,2017-06-02 13:15:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,2017-06-02 13:15:56 - DEBUG createNativeListener: 'Native Server - close'
,# setup
(lldb) ,# terminate an Outgoing connection
(lldb) ,2017-06-02 13:16:01 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 223 Passed bogus id
2017-06-02 13:16:01 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port(lldb) , 901'
,ok 224 Passed good id but bogus port
(lldb) ,2017-06-02 13:16:01 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
,ok 225 Passed right context
(lldb) ,ok 226 Right server
,ok 227 No error should be set
(lldb) ,ok 228 Retry should be false
,ok 229 We called close server
(lldb) ,# teardown
,# setup
(lldb) ,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-06-02 13:16:04 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:16:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# #startListeningForAdvertisements should fail if start not called
(lldb) ,ok 230 specific error should be returned
,# teardown
(lldb) ,ok 231 must be stopped
2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:06 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:06 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-02 13:16:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# #startUpdateAdvertisingAndListening should fail if start not called
,ok 232 specific error should be returned
(lldb) ,# teardown
,ok 233 must be stopped
(lldb) ,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:18 - DE,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:16:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:16:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #stopListeningForAdvertisements many times
,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'listening 50864'
(lldb) ,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 234 no errors
,2017-06-02 13:16:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:16:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 235 still no errors
(lldb) ,# teardown
,2017-06-02 13:16:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-06-02 13:16:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-02 13:16:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false,}'
2017-06-02 13:16:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2017-06-02 13:16:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 236 must be stopped
2017-06-02 13:16:29 - DEBUG thaliMo(lldb) ,bileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:16:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:16:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:16:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:16:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:16:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:16:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #startListeningForAdvertisements many times
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'listening 50867'
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-02 13:16:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 237 no errors
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-06-02 13:16:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 238 still no errors
,# teardown
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
,2017-06-02 13:16:37 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr(lldb) ,et":null,"networkType":null}})'
,2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,2017-06-02 13:16:37 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 239 must be stopped
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:16:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:16:42 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:16:42 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# should be able to call #startUpdateAdvertisingAndListening many times
,2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'listening 50868'
(lldb) ,2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-06-02 13:16:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-06-02 13:16:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 240 no errors
2017-06-02 13:16:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-06-02 13:16:43 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-06-02 13:16:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 241 still no errors
(lldb) ,# teardown
,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-06-02 13:17:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped st,ate).'
2017-06-02 13:17:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 242 must be stopped
2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-06-02 13:17:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-06-02 13:17:03 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-06-02 13:17:04 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-06-02 13:17:04 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-06-02 13:17:04 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-06-02 13:17:04 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-06-02 13:17:04 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# should be able to call #stopAdvertisingAndListening many times
(lldb) 
```
