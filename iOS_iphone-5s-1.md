#### Test 111727539a32d624_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/111727539a32d624/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
,-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/FE1C89A6-9AF8-41FB-9DF8-F4FAA0DE0578/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/FE1C89A6-9AF8-41FB-9DF8-F4FAA0DE0578/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/111727539a32d624/build_ios/ThaliTest.app"
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Current executable set to '/Users/thali/Github/CI/builder/builds/111727539a32d624/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:57128"
,(lldb)     command script import "/tmp/FE1C89A6-9AF8-41FB-9DF8-F4FAA0DE0578/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
(lldb) ,Process ARCH arm64
,JXcore Cordova bridge is ready!
(lldb) ,JXcore engine is started
,2017-03-23 10:39:33 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-23 10:39:33 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:39:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:39:33 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:39:33 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:39:33 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:39:33 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
,AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
(lldb) ,Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
AppContextTests.test_connectReturnValueCo(lldb) ,rrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-03-23 10:39:36 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
Number of ignored tests:  0
Total duration:  1.73157799243927
(lldb) ,2017-03-23 10:39:36 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
,2017-03-23 10:39:36 - WARN testUtils: 'myNameCallback not set!'
(lldb) ,2017-03-23 10:39:39 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-23 10:39:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-23 10:39:39 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-03-23 10:39:40 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-23 10:39:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-23 10:39:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-03-23 10:39:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-23 10:39:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-23 10:39:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-23 10:39:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-23 10:39:41 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-23 10:39:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-23 10:39:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-23 10:39:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-23 10:39:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-23 10:39:42 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-23 10:39:43 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-23 10:39:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-23 10:39:44 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/E21735A6-8341-411D-AA22-2EC501A30A57/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-23 10:39:44 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-03-23 10:39:44 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-03-23 10:39:45 - DEBUG CoordinatedClient: 'connected to the test server'
(lldb) ,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-03-23 10:39:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-03-23 10:39:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 2 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
(lldb) ,2017-03-23 10:40:02 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-03-23 10:40:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-03-23 10:40:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-03-23 10:40:16 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
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
,ok 18 secondPromise setTimeout
ok 19 secondPromise result
ok 20 secondPromise testValue
ok 21 thirdPromise in promise
ok 22 thirdPromise result
ok 23 thirdPromise testValue
(lldb) ,# teardown
,# setup
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
,# setup
(lldb) ,# basic
(lldb) ,ok 41 sane
,# teardown
(lldb) ,# setup
,# another
(lldb) ,ok 42 sane
,# teardown
(lldb) ,# setup
(lldb) ,# can pass data in setup
,ok 43 test participant has uuid
ok 44 participant data matches
ok 45 test participant has uuid
ok 46 participant data matches
ok 47 test participant has uuid
ok 48 participant data matches
ok 49 own UUID is found from the participants list
(lldb) ,# teardown
,# setup
(lldb) ,# Correctly parses/stringifies USN
,ok 50 correctly parses USN string
ok 51 throws if usn has invalid prefix
ok 52 throws if usn has invalid identifier format
(lldb) ,ok 53 throws if usn has invalid generation
ok 54 correctly stringifies peer
,# teardown
(lldb) ,# setup
,# onPeerLost calls jxcore
(lldb) ,2017-03-23 10:41:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
,# teardown
(lldb) ,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:20 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:20 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# onPeerDiscovered calls jxcore
(lldb) ,2017-03-23 10:41:20 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
,# teardown
(lldb) ,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:23 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:23 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-23 10:41:25 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 55 Can call startListeningForAdvertisements without error
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23, 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 56 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 57 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:25 - INFO thal(lldb) ,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 58 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ,e'
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:41:25 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
2017-03-23 10:41:25 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-03-23 10:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-23 10:41:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 59 Can call startListeningForAdvertisements without error
2017-03-23 10:41:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-23 (lldb) ,10:41:29 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,",n(lldb) ,etworkType":null}})'
2017-03-23 10:41:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
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
(lldb) ,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:41:30 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:41:30 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
,2017-03-23 10:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 63 Can call stopListeningForAdvertisements without error
2017-03-23 10:41:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:33 - INFO thaliMobile: 'Fi,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call stopListeningForAdvertisements without error
(lldb) ,# teardown
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-23 10:41:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:41:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:41:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
(lldb) ,2017-03-23 10:41:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:41:39 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 67 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:41:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03(lldb) ,-23 10:41:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-03-23 10:41:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 69 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:41:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:41:40 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:41:40 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
(lldb) ,2017-03-23 10:41:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:41:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:41:47 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-(lldb) ,23 10:41:47 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nul,l(lldb) ,,"networkType":null}})'
,2017-03-23 10:41:47 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 72 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
(lldb) ,2017-03-23 10:41:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:41:51 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:41:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 73 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:41:51 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-03-23 10:41:51 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 74 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:41:51 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,b(lldb) ,ilityChanged registered to native'
2017-03-23 10:41:51 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:41:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:41:51 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:41:51 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:41:51 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:41:51 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:41:51 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
(lldb) ,2017-03-23 10:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:42:05 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 75 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:42:05 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:42:05 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 76 Can call stopAdvertisingAndListening without error
,# teardown
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:42:07 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 77 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-23 10:42:07 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-23 10:42:07 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-23 10:42:07 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# peerAvailabilityChange is called
(lldb) ,2017-03-23 10:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListeningwithout error
(lldb) ,2017-03-23 10:42:12 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-23 10:42:12 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-03-23 10:42:12 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 80 Can call startListeningForAdvertisements without error
(lldb) ,ok 81 peers must be an array
ok 82 peers must not be zero-length
ok 83 peer must have only peerIdentifier, peerAvailable and generation properties
ok 84 peerIdentifier must be a string
ok 85 generation must be a number
,# teardown
(lldb) ,2017-03-23 10:42:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:42:16 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:42:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Should be able to call stopListeningForAdvertisements in teardown
2017-03-23 10:42:16 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-03-23 10:42:16 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Should be able to call stopAdvertisingAndListening in teardown
2017-03-23 10:42:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,bilityChanged registered to native'
(lldb) ,2017-03-23 10:42:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-23 10:42:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-23 10:42:16 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-23 10:42:16 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-23 10:42:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-23 10:42:16 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-23 10:42:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can connect to a remote peer
(lldb) ,2017-03-23 10:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-23 10:42:31 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-23 10:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 88 Can call startUpdateAdvertisingAndListening without error
2017-03-23 10:42:31 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2017-03-2(lldb) ,3 10:42:31 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,,"networkType":null}})'
2017-03-23 10:42:31 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startListeningForAdvertisements without error
(lldb) ,2017-03-23 10:42:32 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"59E2DA66-6364-4DB7-8F52-8DA1759A6190","generation":0}]'
(lldb) ,2017-03-23 10:42:32 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for 59E2DA66-6364-4DB7-8F52-8DA1759A6190 (syncValue: JkoZEqoddN2HW3Srpz82KhXZ00Ao8W4I)'
,2017-03-23 10:42:32 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
(lldb) ,2017-03-23 10:42:32 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"2A1F2E2C-1D58-45B9-A65B-3D0CF00F837F","generation":0}]'
2017-03-23 10:42:32 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"28B24A80-4744-4C5E-BB43-5CBA6A1CA7B0","generation":0}]'
(lldb) ,libc++abi.dylib: terminating with uncaught exception of type NSException
(lldb) ,* thread #1: tid = 0x9f04d, 0x00000001910e1188 libsystem_kernel.dylib`mach_msg_trap + 8, queue = 'com.apple.main-thread'
  * frame #0: 0x00000001910e1188 libsystem_kernel.dylib`mach_msg_trap + 8
    frame #1: 0x00000001920de5d0 CoreFoundation`<redacted> + 192
    frame #2: 0x00000001920dc1ec CoreFoundation`<redacted> + 1132
    frame #3: 0x000000019200a2b8 CoreFoundation`CFRunLoopRunSpecific + 444
    frame #4: 0x0000000193abe198 GraphicsServices`GSEventRunModal + 180
    frame #5: 0x00000001980517fc UIKit`<redacted> + 684
    frame #6: 0x000000019804c534 UIKit`UIApplicationMain + 208
    frame #7: 0x00000001000995ac ThaliTest`main + 76
    frame #8: 0x0000000190fed5b8 libdyld.dylib`<redacted> + 4

```
