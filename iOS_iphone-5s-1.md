#### Test 112761991de7a3d0_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/112761991de7a3d0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/A9706DC5-55EC-4304-9A95-606FAAB421C5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/A9706DC5-55EC-4304-9A95-606FAAB421C5/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
,(lldb)     target create "/Users/thali/Github/CI/builder/builds/112761991de7a3d0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/112761991de7a3d0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52877"
,(lldb)     command script import "/tmp/A9706DC5-55EC-4304-9A95-606FAAB421C5/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
,(lldb)     command script add -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.run_command run
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.safequit_command safequit
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
(lldb) ,2017-03-28 13:47:05 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-28 13:47:05 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-28 13:47:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:47:05 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:47:05 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 13:47:05 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:47:05 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
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
AppContextTests.test_connectReturnValueCo,rrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-03-28 13:47:07 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.370635986328125
,2017-03-28 13:47:07 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
(lldb) ,2017-03-28 13:47:07 - WARN testUtils: 'myNameCallback not set!'
,2017-03-28 13:47:10 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-28 13:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-28 13:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
(lldb) ,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
(lldb) ,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
(lldb) ,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
(lldb) ,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
(lldb) ,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
(lldb) ,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-28 13:47:14 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/EE5B9A1C-F7C3-4FF6-8303-C4F28AF87F0B/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-28 13:47:14 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-03-28 13:47:15 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-03-28 13:47:17 - DEBUG CoordinatedClient: 'connected to the test server'
(lldb) ,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-03-28 13:47:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
,2017-03-28 13:47:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-03-28 13:47:26 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-03-28 13:47:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
,2017-03-28 13:47:34 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
(lldb) ,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-03-28 13:47:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-03-28 13:47:41 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-03-28 13:47:44 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
,ok 4 should be equal
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
(lldb) ,# setup
,# queues handled independently
(lldb) ,ok 40 all short operations completed before the long resolves
# teardown
(lldb) ,# setup
,# basic
(lldb) ,ok 41 sane
,# teardown
(lldb) ,# setup
,# another
(lldb) ,ok 42 sane
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox spy
,2017-03-28 13:48:10 - DEBUG testTests: 'test spy method for global sinon sansbox'
(lldb) ,ok 43 test sandbox spy works correctly
,# teardown
(lldb) ,# setup
,# test sinon sansbox stub
(lldb) ,ok 44 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub override
,ok 45 test sandbox stub works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox mock
(lldb) ,# teardown
(lldb) ,# setup
,# test sinon sansbox restore after test end
(lldb) ,ok 46 test restore
(lldb) ,# teardown
,# setup
(lldb) ,# can pass data in setup
,ok 47 test participant has uuid
ok 48 participant data matches
ok 49 test participant has uuid
ok 50 participant data matches
ok 51 test participant has uuid
ok 52 participant data matches
ok 53 own UUID is found from the participants list
(lldb) ,# teardown
,# setup
(lldb) ,# Correctly parses/stringifies USN
(lldb) ,ok 54 correctly parses USN string
(lldb) ,ok 55 throws if usn has invalid prefix
,ok 56 throws if usn has invalid identifier format
(lldb) ,ok 57 throws if usn has invalid generation
,ok 58 correctly stringifies peer
(lldb) ,# teardown
,# setup
(lldb) ,# onPeerLost calls jxcore
,2017-03-28 13:48:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
(lldb) ,# teardown
,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-03-28 13:48:28 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# onPeerDiscovered calls jxcore
(lldb) ,2017-03-28 13:48:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-03-28 13:48:30 - INFO thaliMobile: 'Filtered out networ(lldb) ,kChangedNonTCP (was in stopped state).'
2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-03-28 13:48:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-28 13:48:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:48:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 59 Can call startListeningForAdvertisements without error
2017-03-28 13:48:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28(lldb) , 13:48:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 60 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-03-28 13:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:32 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 61 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:48:32 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:32 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 13:48:32 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
,2017-03-28 13:48:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:48:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:48:32 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:48:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:48:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:48:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-03-28 13:48:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-28 13:48:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:48:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 63 Can call startListeningForAdvertisements without error
2017-03-28 13:48:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-28 (lldb) ,13:48:35 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-03-28 13:48:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 65 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:36 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:48:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
,2017-03-28 13:48:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 67 Can call stopListeningForAdvertisements without error
2017-03-28 13:48:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:37 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 68 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-03-28 13:48:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 13:48:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopListeningForAdvertisements in teardown
,2017-03-28 13:48:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 70 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 13:48:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 13:48:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAd,vertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:48:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:48:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:48:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:48:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:48:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
,2017-03-28 13:48:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:48:46 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:48:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening without error
2017-03-28 13:48:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03,-28 13:48:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
(lldb) ,2017-03-28 13:48:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 73 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:48:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:51 - INFO thal(lldb) ,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 13:48:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ,e'
2017-03-28 13:48:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-28 13:48:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 13:48:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 13:48:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-28 13:48:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 13:48:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:48:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-03-28 13:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:48:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 75 Can call startUpdateAdvertisingAndListening without error
2017-03-28 13:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-,28 13:48:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nul(lldb) ,l,,"networkType":null}})'
2017-03-28 13:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
(lldb) ,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:48:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:48:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 77 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-03-28 13:48:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Should be able to call stopAdvertisingAndListening in teardown
,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:55 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 13:48:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-03-28 13:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 13:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListening without error
2017-03-28 13:49:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStat(lldb) ,eUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:49:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-03-28 13:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 13:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:49:11 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:49:11 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-28 13:49:11 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 13:49:11 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-28 13:49:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:49:11 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:49:11 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:49:11 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:49:11 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:49:11 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# peerAvailabilityChange is called
,2017-03-28 13:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:49:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:49:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 83 Can call startUpdateAdvertisingAndListeningwithout error
2017-03-28 13:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
(lldb) ,2017-03-28 13:49:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre(lldb) ,t":null,"networkType":null}})'
2017-03-28 13:49:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Can call startListeningForAdvertisements without error
,ok 85 peers must be an array
ok 86 peers must not be zero-length
ok 87 peer must have only peerIdentifier, peerAvailable and generation properties
ok 88 peerIdentifier must be a string
ok 89 generation must be a number
(lldb) ,# teardown
,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-03-28 13:49:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-03-28 13:49:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 90 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:49:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 91 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 13:49:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can connect to a remote peer
(lldb) ,2017-03-28 13:49:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:49:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:49:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 92 Can call startUpdateAdvertisingAndListening without error
,2017-03-28 13:49:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-28 13:49:39 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di(lldb) ,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:49:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat,eUpdate (was in stopped state).'
ok 93 Can call startListeningForAdvertisements without error
(lldb) ,2017-03-28 13:49:39 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"56817EA7-7F4D-40D2-A43D-E645A83262B5","generation":0}]'
2017-03-28 13:49:39 - DEBUG thaliMobileNativeTestUtils: 'Issui,ng multiConnect for 56817EA7-7F4D-40D2-A43D-E645A83262B5 (syncValue: 52GsBdgpS8daMER3pULhJmwEHU4iHBGg)'
2017-03-28 13:49:39 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
(lldb) ,* thread #27: tid = 0x12e57e, 0x00000001910ff014 libsystem_kernel.dylib`__pthread_kill + 8, queue = 'com.apple.MCSession.callbackQueue', stop reason = signal SIGABRT
  * frame #0: 0x00000001910ff014 libsystem_kernel.dylib`__pthread_kill + 8
    frame #1: 0x0000000191073400 libsystem_c.dylib`abort + 140
    frame #2: 0x0000000190b3d2d4 libc++abi.dylib`<redacted> + 132
    frame #3: 0x0000000190b5acc0 libc++abi.dylib`<redacted> + 304
    frame #4: 0x0000000190b68844 libobjc.A.dylib`<redacted> + 124
    frame #5: 0x0000000190b5766c libc++abi.dylib`<redacted> + 16
    frame #6: 0x0000000190b56f84 libc++abi.dylib`__cxa_throw + 136
    frame #7: 0x0000000190b68690 libobjc.A.dylib`objc_exception_throw + 364
    frame #8: 0x000000019200f870 CoreFoundation`<redacted> + 312
    frame #9: 0x000000019201b5fc CoreFoundation`<redacted> + 52
    frame #10: 0x000000010000f3a0 ThaliTest`-[JXcoreExtension(AppContextDelegate) context:didResolveMultiConnectWithSyncValue:error:listeningPort:] + 292
    frame #11: 0x0000000100017a10 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded, Arg[2] = Owned To Guaranteed> of ThaliTest.AppContext.(handleMultiConnectResolved in _F3DAF5A2B391CB31FC98FBDA08CABB7E) (withSyncValue : Swift.String, port : Swift.Optional<Swift.UInt16>, error : Swift.Optional<Swift.Error>) -> () + 484
    frame #12: 0x0000000100019d50 ThaliTest`function signature specialization <Arg[0] = Owned To Guaranteed and Exploded, Arg[1] = Owned To Guaranteed, Arg[3] = Owned To Guaranteed, Arg[4] = Owned To Guaranteed and Exploded> of ThaliTest.AppContext.(multiConnectToPeer (Swift.Array<Swift.AnyObject>, validationCompletionHandler : (Swift.Optional<__ObjC.NSError>) -> ()) -> ()).(closure #1) + 124
    frame #13: 0x0000000100011b48 ThaliTest`ThaliTest.AppContext.(multiConnectToPeer (Swift.Array<Swift.AnyObject>, validationCompletionHandler : (Swift.Optional<__ObjC.NSError>) -> ()) -> ()).(closure #1) + 44
    frame #14: 0x000000010001b614 ThaliTest`partial apply forwarder for ThaliTest.AppContext.(multiConnectToPeer (Swift.Array<Swift.AnyObject>, validationCompletionHandler : (Swift.Optional<__ObjC.NSError>) -> ()) -> ()).(closure #1) with unmangled suffix ".46" + 132
    frame #15: 0x0000000100a89450 ThaliCore`ThaliCore.BrowserManager.(connectToPeer (Swift.String, syncValue : Swift.String, completion : (Swift.String, Swift.Optional<Swift.Error>, Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #1).(closure #1) + 156
    frame #16: 0x0000000100aa4944 ThaliCore`ThaliCore.BrowserRelay.(openRelay (with : (Swift.Optional<Swift.UInt16>, Swift.Optional<Swift.Error>) -> ()) -> ()).(closure #1) + 112
    frame #17: 0x0000000100a7f98c ThaliCore`ThaliCore.TCPListener.startListeningForConnections (on : Swift.UInt16, connectionAccepted : (__ObjC.GCDAsyncSocket) -> (), completion : (Swift.Optional<Swift.UInt16>, Swift.Optional<Swift.Error>) -> ()) -> () + 512
    frame #18: 0x0000000100aa47ac ThaliCore`ThaliCore.BrowserRelay.openRelay (with : (Swift.Optional<Swift.UInt16>, Swift.Optional<Swift.Error>) -> ()) -> () + 304
    frame #19: 0x0000000100a8923c ThaliCore`ThaliCore.BrowserManager.(connectToPeer (Swift.String, syncValue : Swift.String, completion : (Swift.String, Swift.Optional<Swift.Error>, Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #1) + 476
    frame #20: 0x0000000100a893a8 ThaliCore`partial apply forwarder for ThaliCore.BrowserManager.(connectToPeer (Swift.String, syncValue : Swift.String, completion : (Swift.String, Swift.Optional<Swift.Error>, Swift.Optional<Swift.UInt16>) -> ()) -> ()).(closure #1) + 176
    frame #21: 0x0000000100ae22d4 ThaliCore`ThaliCore.Session.(session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChange : __C.MCSessionState) -> ()).(closure #1) + 348
    frame #22: 0x0000000100ae2318 ThaliCore`reabstraction thunk helper from @callee_owned (@inout __C.MCSessionState) -> (@error @owned Swift.Error) to @callee_owned (@inout __C.MCSessionState) -> (@out (), @error @owned Swift.Error) + 36
    frame #23: 0x0000000100adc6c0 ThaliCore`ThaliCore.Atomic.modify <A> (action : (inout A) throws -> A1) throws -> A1 + 136
    frame #24: 0x0000000100ae2140 ThaliCore`ThaliCore.Session.session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChange : __C.MCSessionState) -> () + 664
    frame #25: 0x0000000100ae23d0 ThaliCore`@objc ThaliCore.Session.session (__ObjC.MCSession, peer : __ObjC.MCPeerID, didChange : __C.MCSessionState) -> () + 100
    frame #26: 0x00000001a6e21960 MultipeerConnectivity`<redacted> + 148
    frame #27: 0x0000000190fba1fc libdispatch.dylib`<redacted> + 24
    frame #28: 0x0000000190fba1bc libdispatch.dylib`<redacted> + 16
    frame #29: 0x0000000190fc83dc libdispatch.dylib`<redacted> + 928
    frame #30: 0x0000000190fbd9a4 libdispatch.dylib`<redacted> + 652
    frame #31: 0x0000000190fca34c libdispatch.dylib`<redacted> + 572
    frame #32: 0x0000000190fca0ac libdispatch.dylib`<redacted> + 124
    frame #33: 0x00000001911c32a0 libsystem_pthread.dylib`_pthread_wqthread + 1288

```
