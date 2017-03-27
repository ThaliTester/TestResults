#### Test 109247054fc76087_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/109247054fc76087/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/4D9D8BFB-184C-4B0A-A1F2-46AC8A3B560E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/4D9D8BFB-184C-4B0A-A1F2-46AC8A3B560E/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/109247054fc76087/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/109247054fc76087/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:60024"
,(lldb)     command script import "/tmp/4D9D8BFB-184C-4B0A-A1F2-46AC8A3B560E/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
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
(lldb) ,Process ARCH arm64
(lldb) ,JXcore Cordova bridge is ready!
,JXcore engine is started
(lldb) ,2017-03-27 12:27:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-27 12:27:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-27 12:27:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-27 12:27:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-27 12:27:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-27 12:27:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-27 12:27:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,AppContextTests.test_willEnterBackground finished
(lldb) ,AppContextTests.test_didEnterForeground finished
,AppContextTests.test_didRegisterToNative finished
(lldb) ,AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
(lldb) ,AppContextTests.test_errorDescription finished
,AppContextTests.test_esonValue finished
(lldb) ,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
(lldb) ,2017-03-27 12:27:17 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
,Total duration:  1.429028928279877
(lldb) ,2017-03-27 12:27:17 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-03-27 12:27:17 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-03-27 12:27:20 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-27 12:27:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
(lldb) ,2017-03-27 12:27:20 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-27 12:27:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-27 12:27:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-27 12:27:21 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-27 12:27:22 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-27 12:27:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-27 12:27:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-27 12:27:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-27 12:27:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-27 12:27:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-27 12:27:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-27 12:27:23 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-27 12:27:24 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
(lldb) ,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
(lldb) ,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
(lldb) ,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
(lldb) ,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
(lldb) ,2017-03-27 12:27:25 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-03-27 12:27:25 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-03-27 12:27:25 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
(lldb) ,2017-03-27 12:27:26 - DEBUG CoordinatedClient: 'connected to the test server'
,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-03-27 12:28:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-03-27 12:28:04 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-03-27 12:28:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-03-27 12:28:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-03-27 12:28:15 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-03-27 12:28:19 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-03-27 12:28:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-03-27 12:28:37 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
(lldb) ,ok 4 should be equal
ok 5 should be equal
(lldb) ,ok 6 should be equal
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultAdapter
(lldb) ,ok 7 should be equal
ok 8 should be equal
ok 9 should be equal
ok 10 should be equal
ok 11 should be equal
ok 12 should be equal
(lldb) ,ok 13 should be equal
ok 14 should be equal
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
,ok 25 thirdPromise - in resolve
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
,# teardown
(lldb) ,# setup
,# queues handled independently
(lldb) ,ok 40 all short operations completed before the long resolves
# teardown
(lldb) ,# setup
(lldb) ,# basic
,ok 41 sane
(lldb) ,# teardown
,# setup
(lldb) ,# another
(lldb) ,ok 42 sane
(lldb) ,# teardown
,# setup
(lldb) ,# can pass data in setup
(lldb) ,ok 43 test participant has uuid
ok 44 participant data matches
ok 45 test participant has uuid
ok 46 participant data matches
ok 47 test participant has uuid
ok 48 participant data matches
ok 49 own UUID is found from the participants list
(lldb) ,# teardown
,# setup
(lldb) ,# Correctly parses/stringifies USN
(lldb) ,ok 50 correctly parses USN string
ok 51 throws if usn has invalid prefix
ok 52 throws if usn has invalid identifier format
ok 53 throws if usn has invalid generation
,ok 54 correctly stringifies peer
,# teardown
(lldb) ,# setup
,# onPeerLost calls jxcore
(lldb) ,2017-03-27 12:29:27 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-03-27 12:29:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-03-27 12:29:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-27 12:29:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-27 12:29:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-27 12:29:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-27 12:29:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-27 12:29:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-27 12:29:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# onPeerDiscovered calls jxcore
(lldb) ,2017-03-27 12:29:30 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-03-27 12:29:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-27 12:29:32 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-27 12:29:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-27 12:29:32 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-03-27 12:29:32 - INFO thaliMobile: 'Filtered out (lldb) ,networkChangedNonTCP (was in stopped state).'
2017-03-27 12:29:32 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-27 12:29:32 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-27 12:29:32 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopListeningForAdvertisements
,2017-03-27 12:29:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-27 12:29:34 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-27 12:29:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 55 Can call startListeningForAdvertisements without error
2017-03-27 12:29:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27(lldb) , 12:29:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 56 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-03-27 12:29:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-27 12:29:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 57 Should be able to call stopListeningForAdvertisements in teardown
2017-03-27 12:29:41 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:29:41 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 58 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-27 12:29:41 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-27 12:29:41 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-27 12:29:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-27 12:29:41 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-27 12:29:41 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-27 12:29:41 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-27 12:29:41 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-27 12:29:41 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
,2017-03-27 12:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-27 12:29:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-27 12:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 59 Can call startListeningForAdvertisements without error
2017-03-27 12:29:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-27 (lldb) ,12:29:42 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-03-27 12:29:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 60 Can call startListeningForAdvertisements twice without error
(lldb) ,# teardown
,2017-03-27 12:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:29:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 61 Should be able to call stopListeningForAdvertisements in teardown
2017-03-27 12:29:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:29:43 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Should be able to call stopAdvertisingAndListening in teardown
2017-03-27 12:29:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-03-27 12:29:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-27 12:29:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-27 12:29:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-27 12:29:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-27 12:29:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-27 12:29:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-27 12:29:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 63 Can call stopListeningForAdvertisements without error
2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:29:46 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-27 12:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopListeningForAdvertisements in teardown
2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:29:46 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-27 12:29:46 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-27 12:29:46 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-03-27 12:29:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-27 12:29:49 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-27 12:29:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 67 Can call startUpdateAdvertisingAndListening without error
2017-03-27 12:29:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-27 12:29:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-03-27 12:29:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:29:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 69 Should be able to call stopListeningForAdvertisements in teardown
2017-03-27 12:29:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:29:51 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Should be able to call stopAdvertisingAndListening in teardown
2017-03-27 12:29:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-03-27 12:29:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-27 12:29:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-27 12:29:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-27 12:29:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-27 12:29:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-27 12:29:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-27 12:29:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-03-27 12:29:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-27 12:29:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-27 12:29:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening without error
2017-03-27 12:29:53 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-,27 12:29:53 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nul(lldb) ,l(lldb) ,,"networkType":null}})'
2017-03-27 12:29:53 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening twice without error
(lldb) ,# teardown
,2017-03-27 12:29:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-03-27 12:29:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-03-27 12:29:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopListeningForAdvertisements in teardown
2017-03-27 12:29:54 - DEBUG thaliMobil(lldb) ,eNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:29:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Should be able to call stopA(lldb) ,dvertisingAndListening in teardown
2017-03-27 12:29:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-27 12:29:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered, (lldb) ,to native'
,2017-03-27 12:29:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-27 12:29:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-27 12:29:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-27 12:29:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-27 12:29:54 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-27 12:29:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-03-27 12:30:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:30:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 75 Can call startUpdateAdvertisingAndListening without error
,2017-03-27 12:30:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-27 12:30:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 76 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
(lldb) ,2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning set to false'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll(lldb) , works even with a server that is not listening yet witheatNotRunning set to true'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on a single db change'
2017-03-27 12:31:15 - INFO Coord,inatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes(lldb) , that are in the checkpoints plugin delay interval'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-03,-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultAdapter'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGG(lldb) ,ER result: passed - enqueue and run in order'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwards'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and en,queueAtTop'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - basic'
2017-03-27 12:31:15 - INFO CoordinatedClient: (lldb) ,'***TEST_LOGGER result: passed - another'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies ,U(lldb) ,SN'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
2017-03-27 12:31:15 - INFO Coordi,natedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
(lldb) ,2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
,2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
(lldb) ,2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
,2017-03-27 12:31:15 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bun(lldb) ,dle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app,/www/jxcore/node_modules/bluebird/js/release/timers.js:49:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.(lldb) ,js:120:1
''
,2017-03-27 12:31:15 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
(lldb) ,2017-03-27 12:32:16 - DEBUG CoordinatedClient: 'all tests completed'
(lldb) ,2017-03-27 12:32:25 - DEBUG CoordinatedClient: 'test client disconnected'
2017-03-27 12:32:25 - DEBUG CoordinatedClient: 'test client failed'
(lldb) ,2017-03-27 12:32:25 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Error: retry count exceed', stack: 'CoordinatedClient.prototype._customError@/private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/j,xcore/lib/CoordinatedClient.js:291:27
Emitter.prototype.emit@/private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7
Socket.prototype.onevent@/private/var/cont(lldb) ,ainers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/node_modules/socket.io-client/lib/socket.js:263:5
Socket.prototype.onpacket@/private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.a,pp/www/jxcore/node_modules/socket.io-client/lib/socket.js:221:7
module.exports/<@/private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/node_modules/component-bind/index.js:21:12
Emitter.prototype.emit@/(lldb) ,private/var/containers/Bundle/Application/46A3E13E-98C4-4B67-B33A-F3A481FF936E/ThaliTest.app/www/jxcore/node_modules/component-emitter/index.js:131:7''
2017-03-27 12:32:25 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'

```
