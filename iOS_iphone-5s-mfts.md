#### Test 112761991de7a3d0_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/112761991de7a3d0/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/78EF17EA-A06A-4CA7-9CD7-634AF8986081/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/78EF17EA-A06A-4CA7-9CD7-634AF8986081/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/112761991de7a3d0/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/112761991de7a3d0/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:52875"
,(lldb)     command script import "/tmp/78EF17EA-A06A-4CA7-9CD7-634AF8986081/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.safequit_command safequit
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
,2017-03-28 13:47:02 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-28 13:47:02 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-28 13:47:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:47:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:47:02 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 13:47:02 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:47:02 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
,AppContextTests.test_thaliCoreErrors finished
AppContextTests.test_errorDescription finished
(lldb) AppContextTests.test_esonValue finished
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
,2017-03-28 13:47:04 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.508595049381256
(lldb) ,2017-03-28 13:47:04 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-03-28 13:47:04 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-03-28 13:47:08 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-28 13:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-28 13:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-28 13:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-28 13:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-28 13:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-28 13:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-28 13:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-28 13:47:08 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-28 13:47:09 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-28 13:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-28 13:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-28 13:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-28 13:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-28 13:47:10 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-28 13:47:11 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-28 13:47:12 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/C1390223-B3E0-49AB-848C-8DA79C4E5711/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-28 13:47:12 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-03-28 13:47:12 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-03-28 13:47:13 - DEBUG CoordinatedClient: 'connected to the test server'
(lldb) ,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-03-28 13:47:21 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
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
(lldb) ,2017-03-28 13:47:35 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
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
,# setup
(lldb) ,# basic
(lldb) ,ok 41 sane
,# teardown
(lldb) ,# setup
,# another
(lldb) ,ok 42 sane
,# teardown
(lldb) ,# setup
(lldb) ,# test sinon sansbox spy
(lldb) ,2017-03-28 13:48:09 - DEBUG testTests: 'test spy method for global sinon sansbox'
,ok 43 test sandbox spy works correctly
(lldb) ,# teardown
,# setup
(lldb) ,# test sinon sansbox stub
(lldb) ,ok 44 test sandbox stub works correctly
,# teardown
(lldb) ,# setup
,# test sinon sansbox stub override
(lldb) ,ok 45 test sandbox stub works correctly
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
(lldb) ,ok 47 test participant has uuid
ok 48 participant data matches
ok 49 test participant has uuid
ok 50 participant data matches
ok 51 test participant has uuid
ok 52 participant data matches
ok 53 own UUID is found from the participants list
,# teardown
(lldb) ,# setup
,# Correctly parses/stringifies USN
(lldb) ,ok 54 correctly parses USN string
ok 55 throws if usn has invalid prefix
ok 56 throws if usn has invalid identifier format
(lldb) ,ok 57 throws if usn has invalid generation
ok 58 correctly stringifies peer
,# teardown
(lldb) ,# setup
,# onPeerLost calls jxcore
(lldb) ,2017-03-28 13:48:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:48:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:48:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# onPeerDiscovered calls jxcore
(lldb) ,2017-03-28 13:48:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:48:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:48:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopListeningForAdvertisements
,2017-03-28 13:48:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-28 13:48:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:48:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 59 Can call startListeningForAdvertisements without error
2017-03-28 13:48:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28(lldb) , 13:48:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 60 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-03-28 13:48:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 61 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-03-28 13:48:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 62 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 13:48:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 13:48:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAd(lldb) ,vertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 13:48:34 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 13:48:34 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-28 13:48:34 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 13:48:34 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:48:34 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
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
2017-03-28 13:48:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 65 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:36 - INFO thal(lldb) ,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Should be able to call stopAdvertisingAndListening in teardown
2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ,e'
2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 13:48:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:48:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-03-28 13:48:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-03-28 13:48:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 67 Can call stopListeningForAdvertisements without error
2017-03-28 13:48:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpd(lldb) ,ateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-03-28 13:48:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 13:48:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:48:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-28 13:48:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 13:48:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-28 13:48:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:48:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:48:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:48:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:48:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:48:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-03-28 13:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:48:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening without error
2017-03-28 13:48:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 13:48:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 72 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-03-28 13:48:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 13:48:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 73 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:48:50 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:48:50 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-28 13:48:50 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 13:48:50 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:50 -(lldb) , DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-28 13:48:50 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-28 13:48:50 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-28 13:48:50 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-28 13:48:50 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-28 13:48:50 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-03-28 13:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:48:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 75 Can call startUpdateAdvertisingAndListening without error
2017-03-28 13:48:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-,28 13:48:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null(lldb) ,,"networkType":null}})'
,2017-03-28 13:48:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Can call startUpdateAdvertisingAndListening twice without error
(lldb) ,# teardown
,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:48:55 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:48:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 77 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-03-28 13:48:55 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Should be able to call stopAdvertisingAndListening in teardown
,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 13:48:55 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:48:55 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:48:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-03-28 13:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:49:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 79 Can call startUpdateAdvertisingAndListening without error
2017-03-28 13:49:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:49:06 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-03-28 13:49:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-28 13:49:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 81 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:49:10 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-28 13:49:10 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 82 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-28 13:49:10 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-28 13:49:10 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-28 13:49:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:49:10 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:49:10 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:49:10 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:49:10 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:49:10 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# peerAvailabilityChange is called
(lldb) ,2017-03-28 13:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:49:13 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:49:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 83 Can call startUpdateAdvertisingAndListeningwithout error
2017-03-28 13:49:13 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-28, 13:49:13 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"(lldb) ,networkType":null}})'
2017-03-28 13:49:13 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 84 Can call startListeningForAdvertisements without error
,ok 85 peers must be an array
(lldb) ,ok 86 peers must not be zero-length
(lldb) ,ok 87 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 88 peerIdentifier must be a string
(lldb) ,ok 89 generation must be a number
,# teardown
(lldb) ,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:49:14 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:49:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 90 Should be able to call stopListeningForAdvertisements in teardown
2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}',
2017-03-28 13:49:14 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 91 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-28 13:49:14 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-28 13:49:14 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can connect to a remote peer
(lldb) ,2017-03-28 13:49:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-28 13:49:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:49:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 92 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-03-28 13:49:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-28 13:49:33 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-28 13:49:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat(lldb) ,eUpdate (was in stopped state).'
ok 93 Can call startListeningForAdvertisements without error
,2017-03-28 13:49:33 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"56817EA7-7F4D-40D2-A43D-E645A83262B5","generation":0}]'
2017-03-28 13:49:33 - DEBUG thaliMobileNativeTestUtils: 'Issui(lldb) ,ng multiConnect for 56817EA7-7F4D-40D2-A43D-E645A83262B5 (syncValue: PYuMWqWNVi5w0K7KSTetegl0nChkZZkQ)'
2017-03-28 13:49:33 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,libc++abi.dylib: terminating with uncaught exception of type NSException
(lldb) ,* thread #1: tid = 0x1296a4, 0x0000000191b79188 libsystem_kernel.dylib`mach_msg_trap + 8, queue = 'com.apple.main-thread'
  * frame #0: 0x0000000191b79188 libsystem_kernel.dylib`mach_msg_trap + 8
    frame #1: 0x0000000192b765d0 CoreFoundation`<redacted> + 192
    frame #2: 0x0000000192b741ec CoreFoundation`<redacted> + 1132
    frame #3: 0x0000000192aa22b8 CoreFoundation`CFRunLoopRunSpecific + 444
    frame #4: 0x0000000194556198 GraphicsServices`GSEventRunModal + 180
    frame #5: 0x0000000198ae97fc UIKit`<redacted> + 684
    frame #6: 0x0000000198ae4534 UIKit`UIApplicationMain + 208
    frame #7: 0x000000010008d218 ThaliTest`main + 76
    frame #8: 0x0000000191a855b8 libdyld.dylib`<redacted> + 4

```
