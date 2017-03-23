#### Test 111727539a32d624_iOS_iphone-5s-mfts Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/111727539a32d624/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,(lldb) command source -s 0 '/tmp/E3E81AFE-A619-407F-86B1-E79A98C25FDD/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'
,Executing commands in '/tmp/E3E81AFE-A619-407F-86B1-E79A98C25FDD/fruitstrap-lldb-prep-cmds-bffa901fefdea07f59339a6737776943349f5077'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/111727539a32d624/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/111727539a32d624/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57126"
,(lldb)     command script import "/tmp/E3E81AFE-A619-407F-86B1-E79A98C25FDD/fruitstrap_bffa901fefdea07f59339a6737776943349f5077.py"
,(lldb)     command script add -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.connect_command connect
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_bffa901fefdea07f59339a6737776943349f5077.autoexit_command autoexit
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
(lldb) ,2017-03-23 10:39:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-23 10:39:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:39:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:39:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:39:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:39:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:39:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
AppContextTests.test_getIOSVersion finished
AppContextTests.test_thaliCoreErrors finished
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
AppContextTests.test_connectReturnValueCo(lldb) ,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-03-23 10:39:26 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.582857012748718
(lldb) ,2017-03-23 10:39:26 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-mfts''
,2017-03-23 10:39:26 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-03-23 10:39:29 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-23 10:39:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-23 10:39:29 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-03-23 10:39:30 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-23 10:39:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-23 10:39:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-03-23 10:39:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-23 10:39:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-23 10:39:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-23 10:39:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-23 10:39:31 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-23 10:39:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-23 10:39:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-23 10:39:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-23 10:39:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-23 10:39:32 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
(lldb) ,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
(lldb) ,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
(lldb) ,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
(lldb) ,2017-03-23 10:39:33 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
,2017-03-23 10:39:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
(lldb) ,2017-03-23 10:39:34 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
,2017-03-23 10:39:34 - DEBUG UnitTest_app: 'Unit Test app is loaded'
(lldb) ,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
,2017-03-23 10:39:34 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
(lldb) ,2017-03-23 10:39:35 - DEBUG CoordinatedClient: 'connected to the test server'
(lldb) ,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-03-23 10:39:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
,2017-03-23 10:40:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 2 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-03-23 10:40:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
,ok 3 Got the right error
# teardown
(lldb) ,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-03-23 10:40:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
,2017-03-23 10:40:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
(lldb) ,# teardown
,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-03-23 10:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-03-23 10:40:17 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
(lldb) ,2017-03-23 10:40:26 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultDirectory
,ok 4 should be equal
(lldb) ,ok 5 should be equal
ok 6 should be equal
,# teardown
(lldb) ,# setup
(lldb) ,# test defaultAdapter
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
(lldb) ,ok 26 secondPromise - second to run
,ok 27 secondPromise - in catch
(lldb) ,ok 28 firstPromise - third to run
,ok 29 firstPromise - in then
(lldb) ,ok 30 testing promises
,# teardown
(lldb) ,# setup
(lldb) ,# mix enqueue and enqueueAtTop
(lldb) ,ok 31 fourth
(lldb) ,ok 32 fourth
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
(lldb) ,# basic
(lldb) ,ok 41 sane
,# teardown
(lldb) ,# setup
,# another
(lldb) ,ok 42 sane
(lldb) ,# teardown
,# setup
(lldb) ,# can pass data in setup
,ok 43 test participant has uuid
ok 44 participant data matches
ok 45 test participant has uuid
ok 46 participant data matches
ok 47 test participant has uuid
ok 48 participant data matches
ok 49 own UUID is found from the participants list
,# teardown
(lldb) ,# setup
,# Correctly parses/stringifies USN
(lldb) ,ok 50 correctly parses USN string
ok 51 throws if usn has invalid prefix
ok 52 throws if usn has invalid identifier format
ok 53 throws if usn has invalid generation
,ok 54 correctly stringifies peer
(lldb) ,# teardown
,# setup
(lldb) ,# onPeerLost calls jxcore
(lldb) ,2017-03-23 10:41:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:20 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# onPeerDiscovered calls jxcore
,2017-03-23 10:41:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
(lldb) ,# teardown
(lldb) ,2017-03-23 10:41:24 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-23 10:41:24 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:24 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:24 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:24 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:24 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:24 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-23 10:41:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 55 Can call startListeningForAdvertisements without error
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 56 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 57 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 58 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-03-23 10:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-23 10:41:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 59 Can call startListeningForAdvertisements without error
2017-03-23 10:41:28 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-23 (lldb) ,10:41:28 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-03-23 10:41:28 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 60 Can call startListeningForAdvertisements twice without error
,# teardown
(lldb) ,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:30 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 61 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:30 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:41:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling stopListeningForAdvertisements without calling start is NOT an error
(lldb) ,2017-03-23 10:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:34 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 63 Can call stopListeningForAdvertisements without error
2017-03-23 10:41:34 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:34 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 64 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-03-23 10:41:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti(lldb) ,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Should be able to call stopAdvertisingAndListening in teardow,n
2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-03-23 10:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:41:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 67 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:41:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03,-23 10:41:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 68 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-03-23 10:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:43 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 69 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:43 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:43 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:41:43 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-03-23 10:41:43 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:41:43 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:41:43 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:41:43 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:41:43 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:41:43 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,2017-03-23 10:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:41:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:41:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-(lldb) ,23 10:41:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nul,l(lldb) ,,"networkType":null}})'
2017-03-23 10:41:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 72 Can call startUpdateAdvertisingAndListening twice without error
(lldb) ,# teardown
,2017-03-23 10:41:48 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:41:48 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:48 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 73 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-03-23 10:41:49 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,bilityChanged registered to native'
2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to(lldb) , native'
,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:49 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-03-23 10:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:42:06 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 75 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:42:06 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:42:06 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 76 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-23 10:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 77 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-03-23 10:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 78 Should be able to call stopAdvertisingAndListening in teardown
,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:42:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# peerAvailabilityChange is called
(lldb) ,2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
(lldb) ,2017-03-23 10:42:15 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
(lldb) ,2017-03-23 10:42:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListeningwithout error
2017-03-23 10:42:15 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-03-23 10:42:15 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre(lldb) ,t":null,"networkType":null}})'
,2017-03-23 10:42:15 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 80 Can call startListeningForAdvertisements without error
,ok 81 peers must be an array
(lldb) ,ok 82 peers must not be zero-length
ok 83 peer must have only peerIdentifier, peerAvailable and generation properties
,ok 84 peerIdentifier must be a string
(lldb) ,ok 85 generation must be a number
,# teardown
(lldb) ,2017-03-23 10:42:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:42:17 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
,2017-03-23 10:42:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 86 Should be able to call stopListeningForAdvertisements in teardown
,2017-03-23 10:42:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:42:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 87 Should be able to call stopAdvertisingAndListening in teardown
(lldb) ,2017-03-23 10:42:17 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:42:17 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:42:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:42:17 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700_GUEST","bssid":"f0:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:42:17 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:42:17 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:42:17 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:42:17 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can connect to a remote peer
(lldb) ,2017-03-23 10:42:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:42:26 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:42:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 88 Can call startUpdateAdvertisingAndListening without error
(lldb) ,2017-03-23 10:42:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-23 10:42:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) di,d not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:42:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStat(lldb) ,eUpdate (was in stopped state).'
ok 89 Can call startListeningForAdvertisements without error
,2017-03-23 10:42:27 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"28B24A80-4744-4C5E-BB43-5CBA6A1CA7B0","generation":0}]'
(lldb) ,2017-03-23 10:42:27 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 28B24A80-4744-4C5E-BB43-5CBA6A1CA7B0 (syncValue: W3KLS4nR925Eu2IZJvGQ32092XkPyjMD)'
,2017-03-23 10:42:27 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
(lldb) ,2017-03-23 10:42:30 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"2A1F2E2C-1D58-45B9-A65B-3D0CF00F837F","generation":0}]'
(lldb) ,2017-03-23 10:42:32 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"6B654D4D-913C-4A9B-9D40-65338F4A5793","generation":0}]'
(lldb) ,2017-03-23 10:42:39 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":false,"peerIdentifier":"6B654D4D-913C-4A9B-9D40-65338F4A5793","generation":0}]'
(lldb) ,2017-03-23 10:42:49 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":false,"peerIdentifier":"28B24A80-4744-4C5E-BB43-5CBA6A1CA7B0","generation":0}]'
(lldb) ,2017-03-23 10:42:54 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":false,"peerIdentifier":"2A1F2E2C-1D58-45B9-A65B-3D0CF00F837F","generation":0}]'
(lldb) ,2017-03-23 10:44:23 - DEBUG CoordinatedClient: 'device disconnected from the test server'
(lldb) ,2017-03-23 10:44:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:44:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:44:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:44:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:44:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:44:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:44:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:44:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:44:56 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:44:56 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:45:06 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:45:06 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:45:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:45:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:45:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:45:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:45:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:45:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:45:47 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:45:47 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:45:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:45:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:46:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:46:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:46:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:46:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:46:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:46:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:46:54 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:46:54 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:47:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:47:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:47:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:47:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:47:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:47:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:47:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:47:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-4(lldb) ,5CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var(lldb) ,/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:47:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:47:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:47:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:47:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:48:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:48:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:48:16 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:48:16 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:48:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:48:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:48:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:48:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:49:03 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:49:03 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:49:13 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:49:13 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:49:24 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:49:24 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:49:34 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:49:34 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:49:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:49:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:49:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:49:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:50:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:50:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:50:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:50:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-4(lldb) ,5CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var(lldb) ,/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:50:25 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:50:25 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:50:35 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:50:35 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:50:45 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:50:45 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:50:55 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:50:55 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:51:05 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:51:05 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:51:15 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:51:15 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:51:26 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:51:26 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:51:36 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:51:36 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:51:46 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:51:46 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:51:57 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:51:57 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:52:07 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:52:07 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:52:17 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:52:17 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll can close even when connections open'
(lldb) ,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll with promise'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll properly throws when closing a non open server with eatNotRunning, set to false'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - closeAll works even with a server that is not listening yet witheatNotRunning set to true'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result:(lldb) , skipped - Call of onCheckpointReached handler on a single db change'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of multiple onCheckpointReached handlers on a single db change'
2017-03-23 10:52:19 - INFO Coordina,tedClient: '***TEST_LOGGER result: skipped - Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - Call of onCheckpoin(lldb) ,t,Reached handler on multiple db changes that are out of the checkpoints plugin delay interval'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - test defaultDirectory'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOG(lldb) ,GER result: passed - test defaultAdapter'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueue and run in order'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - enqueueAtTop and run backwar,ds'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - mix enqueue and enqueueAtTop'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - queues handled independently'
2017-03-23 10:52:19 - INFO Coor(lldb) ,dinatedClient: '***TEST_LOGGER result: passed - basic'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - another'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - can pass data in setup'
2017-0,3-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Correctly parses/stringifies USN'
2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerLost calls jxcore'
(lldb) ,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: skipped - onPeerDiscovered calls jxcore'
,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopListeningForAdvertisements'
(lldb) ,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startListeningForAdvertisements twice is NOT an error'
,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling stopListeningForAdvertisements without calling start is NOT an error'
(lldb) ,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call start/stopUpdateAdvertisingAndListening'
,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Calling startUpdateAdvertisingAndListening twice is NOT an error'
(lldb) ,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - Can call stopUpdateAdvertisingAndListening twice without start and it is not an error'
,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: passed - peerAvailabilityChange is called'
(lldb) ,2017-03-23 10:52:19 - INFO CoordinatedClient: '***TEST_LOGGER result: failed - Can connect to a remote peer, error: 'TimeoutError', stack: 'TimeoutError: 
    at SubError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/Thal,iTest.app/www/jxcore/node_modules/bluebird/js/release/errors.js:15:13
    at module.exports/afterTimeout@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:49(lldb) ,:15
    at timeoutTimeout@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/bluebird/js/release/timers.js:76:13
    at $9@timers.js:120:1
''
,2017-03-23 10:52:19 - ERROR CoordinatedClient: 'failed to run unit tests, platformName: 'ios''
(lldb) ,2017-03-23 10:52:27 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:52:27 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:52:38 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:52:38 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:52:48 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:52:48 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:52:58 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:52:58 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:53:08 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:53:08 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:53:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:53:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:53:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:53:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:53:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:53:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:53:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:53:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:53:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:53:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:54:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:54:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:54:19 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_(lldb) ,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:54:19 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w(lldb) ,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:54:29 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:54:29 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:54:39 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:54:39 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:54:49 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:54:49 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:54:59 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:54:59 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:55:09 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:55:09 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:55:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:55:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:55:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:55:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:55:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:55:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:55:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:55:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:56:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:56:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:56:10 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:56:10 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:56:20 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:56:20 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:56:30 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:56:30 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:56:40 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:56:40 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:56:50 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:56:50 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:57:00 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:57:00 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:57:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:57:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:57:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:57:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:57:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:57:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:57:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:57:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:57:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:57:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:58:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:58:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:58:11 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:58:11 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-4(lldb) ,5CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/nod,e_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var(lldb) ,/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:58:21 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:58:21 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W(lldb) ,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu(lldb) ,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:58:31 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:58:31 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/(lldb) ,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:58:41 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:58:41 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) ,2017-03-23 10:58:51 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:58:51 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:59:01 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:59:01 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,ebsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
(lldb) ,WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/,Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_mod(lldb) ,ules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
,2017-03-23 10:59:12 - WARN CoordinatedClient: 'connect_error error ignored for reconnect: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45C(lldb) ,A-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
WS.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_,modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/c(lldb) ,ontainers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
2017-03-23 10:59:12 - WARN CoordinatedClient: 'reconnect_error error ignored for reconnect: 'Error: w,e(lldb) ,bsocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
W,S.prototype.addEventListeners/this.ws.onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
onError@/private/var/containers/Bundle/A(lldb) ,pplication/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
emit@events.js:82:1
onerror@/private/var/containers/Bundle/Application/E447340B-4A31-45CA-99E8-D67ABB3741F6/ThaliTest.app/www/jxcore/node_modu,les/ws/lib/WebSocket.js:686:5
emit@events.js:82:1''
(lldb) 
```
