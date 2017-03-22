#### Test 1119938693313880_iOS_iphone-5s-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/1119938693313880/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of iPhone 5s (Global/CDMA) 'iphone-5s-1' (00b2e2c1b30013159b62125fe7f097bdcc055c10) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 5s (Global/CDMA) 'iphone-5s-mfts' (bffa901fefdea07f59339a6737776943349f5077).
,(lldb) command source -s 0 '/tmp/D5787820-8DC0-4B6D-A377-9282FB09EB00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'
,Executing commands in '/tmp/D5787820-8DC0-4B6D-A377-9282FB09EB00/fruitstrap-lldb-prep-cmds-00b2e2c1b30013159b62125fe7f097bdcc055c10'.
,(lldb)     platform select remote-ios --sysroot '/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Applications/Xcode.app/Contents/Developer/Platforms/iPhoneOS.platform/DeviceSupport/10.2 (14C89)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/1119938693313880/build_ios/ThaliTest.app"
,Skipping J81AP 'ipad-air-2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe).
,Current executable set to '/Users/thali/Github/CI/builder/builds/1119938693313880/build_ios/ThaliTest.app' (arm64).
(lldb)     script fruitstrap_device_app="/private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:50876"
,(lldb)     command script import "/tmp/D5787820-8DC0-4B6D-A377-9282FB09EB00/fruitstrap_00b2e2c1b30013159b62125fe7f097bdcc055c10.py"
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
,2017-03-22 12:42:49 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
(lldb) ,2017-03-22 12:42:49 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-22 12:42:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-22 12:42:49 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-22 12:42:49 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-22 12:42:49 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-22 12:42:49 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,AppContextTests.test_willEnterBackground finished
,AppContextTests.test_didEnterForeground finished
(lldb) ,AppContextTests.test_didRegisterToNative finished
,AppContextTests.test_getIOSVersion finished
(lldb) ,AppContextTests.test_thaliCoreErrors finished
,AppContextTests.test_errorDescription finished
(lldb) ,AppContextTests.test_esonValue finished
,Optional(true)
Optional(false)
(lldb) ,AppContextTests.test_listeningAdvertisingUpdateOnStartAdvertising finished
,Optional(false)
Optional(true)
AppContextTests.test_listeningAdvertisingUpdateOnStartListening finished
(lldb) ,AppContextTests.test_startAdvertisingAndListeningInvokePeerAvailabilityChangedForDifferentContexts finished
AppContextTests.test_peerAvailabilityConversion finished
AppContextTests.test_disconnectErrors finished
(lldb) ,AppContextTests.test_connectReturnValueCorrect finished
AppContextTests finished
All tests finished
All tests finished
,2017-03-22 12:42:52 - DEBUG UnitTest_app: 'Running unit tests'
*Native tests were executed*
Total number of executed tests:  13
Number of passed tests:  13
Number of failed tests:  0
(lldb) ,Number of ignored tests:  0
Total duration:  1.372332096099854
,2017-03-22 12:42:52 - DEBUG UnitTest_app: 'My device name is: 'Apple-iphone-5s-1''
(lldb) ,2017-03-22 12:42:52 - WARN testUtils: 'myNameCallback not set!'
,2017-03-22 12:42:55 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: ios'
(lldb) ,2017-03-22 12:42:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
,2017-03-22 12:42:55 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
(lldb) ,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testPouchDBGenerator.js'
,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js'
(lldb) ,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testTests.js'
,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testUsn.js'
(lldb) ,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testNativeMethod.js'
,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNative.js'
(lldb) ,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
(lldb) ,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
,2017-03-22 12:42:56 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testCreateNativeListener.js'
(lldb) ,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testCreatePeerListener.js'
,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliTcpServersManager.js'
(lldb) ,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
(lldb) ,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliMobile.js'
,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerAction.js'
(lldb) ,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerDictionary.js'
,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
(lldb) ,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
(lldb) ,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotification.js'
,2017-03-22 12:42:57 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationAction.js'
(lldb) ,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
(lldb) ,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationClient.js'
,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationLocal.js'
(lldb) ,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliNotificationServer.js'
,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
(lldb) ,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
(lldb) ,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
(lldb) ,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManager.js'
(lldb) ,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliManager.js'
(lldb) ,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
,2017-03-22 12:42:59 - INFO testLoader: 'loading file: /private/var/containers/Bundle/Application/40479B26-CCF0-42E6-9BA5-636F44349764/ThaliTest.app/www/jxcore/bv_tests/testSSDPServer.js'
(lldb) ,2017-03-22 12:42:59 - DEBUG UnitTest_app: 'Unit Test app is loaded'
,appEnteringBackground wasn't registered
appEnteredForeground wasn't registered
(lldb) ,2017-03-22 12:43:00 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
,2017-03-22 12:43:00 - DEBUG CoordinatedClient: 'connected to the test server'
(lldb) ,TAP version 13
(lldb) ,# setup
,# closeAll can close even when connections open
(lldb) ,2017-03-22 12:43:16 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 1 not possible to connect to the server anymore
# teardown
,# setup
(lldb) ,# closeAll with promise
(lldb) ,2017-03-22 12:43:19 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
(lldb) ,ok 2 not possible to connect to the server anymore
,# teardown
(lldb) ,# setup
(lldb) ,# closeAll properly throws when closing a non open server with eatNotRunning set to false
,2017-03-22 12:43:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 3 Got the right error
(lldb) ,# teardown
,# setup
(lldb) ,# closeAll works even with a server that is not listening yet witheatNotRunning set to true
(lldb) ,2017-03-22 12:43:24 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
,# setup
(lldb) ,# Call of onCheckpointReached handler on a single db change
(lldb) ,2017-03-22 12:43:28 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on a single db change''
,# teardown
(lldb) ,# setup
,# Call of multiple onCheckpointReached handlers on a single db change
(lldb) ,2017-03-22 12:43:29 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of multiple onCheckpointReached handlers on a single db change''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
(lldb) ,2017-03-22 12:43:38 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval''
,# teardown
(lldb) ,# setup
(lldb) ,# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
,2017-03-22 12:43:39 - DEBUG CoordinatedClient: 'test was skipped, name: 'Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval''
(lldb) ,# teardown
,# setup
(lldb) ,# test defaultDirectory
,ok 4 should be equal
(lldb) ,ok 5 should be equal
ok 6 should be equal
,# teardown
(lldb) ,# setup
,# test defaultAdapter
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
,# enqueue and run in order
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
(lldb) ,# enqueueAtTop and run backwards
(lldb) ,ok 24 thirdPromise - first to run
(lldb) ,ok 25 thirdPromise - in resolve
ok 26 secondPromise - second to run
ok 27 secondPromise - in catch
ok 28 firstPromise - third to run
ok 29 firstPromise - in then
ok 30 testing promises
,# teardown
(lldb) ,# setup
,# mix enqueue and enqueueAtTop
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
(lldb) ,# queues handled independently
,ok 40 all short operations completed before the long resolves
# teardown
(lldb) ,# setup
(lldb) ,# basic
,ok 41 sane
(lldb) ,# teardown
,# setup
(lldb) ,# another
,ok 42 sane
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
,ok 53 throws if usn has invalid generation
ok 54 correctly stringifies peer
,# teardown
(lldb) ,# setup
(lldb) ,# onPeerLost calls jxcore
,2017-03-22 12:44:12 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerLost calls jxcore''
(lldb) ,# teardown
(lldb) ,2017-03-22 12:44:13 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
,2017-03-22 12:44:13 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-22 12:44:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-22 12:44:13 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-22 12:44:13 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-22 12:44:13 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-22 12:44:13 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-22 12:44:13 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# onPeerDiscovered calls jxcore
,2017-03-22 12:44:14 - DEBUG CoordinatedClient: 'test was skipped, name: 'onPeerDiscovered calls jxcore''
(lldb) ,# teardown
,2017-03-22 12:44:15 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-22 12:44:15 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2017-03-22 12:44:15 - DE(lldb) ,BUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-22 12:44:15 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
2017-03-22 12:44:15 - INFO thaliMobile: 'Filtered out networ(lldb) kChangedNonTCP (was in stopped state).'
2017-03-22 12:44:15 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-22 12:44:15 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-22 12:44:15 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Can call start/stopListeningForAdvertisements
(lldb) ,2017-03-22 12:44:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-22 12:44:17 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-22 12:44:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 55 Can call startListeningForAdvertisements without error
(lldb) ,2017-03-22 12:44:17 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:17 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 56 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-03-22 12:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
,2017-03-22 12:44:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 57 Should be able to call stopListeningForAdvertisements in teardown
2017-03-22 12:44:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti(lldb) ,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 58 Should be able to call stopAdvertisingAndListening in teardow,n
2017-03-22 12:44:18 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-22 12:44:18 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-22 12:44:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-22 12:44:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-22 12:44:18 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-22 12:44:18 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-22 12:44:18 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-22 12:44:18 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# Calling startListeningForAdvertisements twice is NOT an error
(lldb) ,2017-03-22 12:44:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2017-03-22 12:44:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-22 12:44:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 59 Can call startListeningForAdvertisements without error
2017-03-22 12:44:20 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
(lldb) ,2017-03-22 12:44:20 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecr,et":null,"networkType":null}})'
2017-03-22 12:44:20 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 60 Can call startListeningForAdvertisements twice without error
(lldb) ,# teardown
,2017-03-22 12:44:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:21 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 61 Should be able to call stopListeningForAdvertisements in teardown
2017-03-22 12:44:21 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:21 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 62 Should be able to call stopAdvertisingAndListening in teardown
2017-03-22 12:44:21 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-03-22 12:44:21 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-22 12:44:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-22 12:44:21 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-22 12:44:21 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-22 12:44:21 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-22 12:44:21 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-22 12:44:21 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling stopListeningForAdvertisements without calling start is NOT an error
,2017-03-22 12:44:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:23 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 63 Can call stopListeningForAdvertisements without error
2017-03-22 12:44:23 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:23 - INFO thaliMobile: 'Fi(lldb) ,ltered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 64 Can call stopListeningForAdvertisements without error
,# teardown
(lldb) ,2017-03-22 12:44:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-22 12:44:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 65 Should be able to call stopListeningForAdvertisements in teardown
2017-03-22 12:44:29 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:29 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 66 Should be able to call stopAdvertisingAndListening in teardow(lldb) ,n
2017-03-22 12:44:29 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-22 12:44:29 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-22 12:44:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-22 12:44:29 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-22 12:44:29 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-22 12:44:29 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-22 12:44:29 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-22 12:44:29 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call start/stopUpdateAdvertisingAndListening
,2017-03-22 12:44:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-22 12:44:33 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-22 12:44:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 67 Can call startUpdateAdvertisingAndListening without error
2017-03-22 12:44:33 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03,-22 12:44:33 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 68 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-03-22 12:44:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 69 Should be able to call stopListeningForAdvertisements in teardown
2017-03-22 12:44:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:35 - INFO thal,iMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 70 Should be able to call stopAdvertisingAndListening in teardown
2017-03-22 12:44:35 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to nativ(lldb) ,e'
2017-03-22 12:44:35 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
,2017-03-22 12:44:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-22 12:44:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-22 12:44:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-22 12:44:35 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-22 12:44:35 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-22 12:44:35 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Calling startUpdateAdvertisingAndListening twice is NOT an error
,2017-03-22 12:44:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-22 12:44:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-22 12:44:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 71 Can call startUpdateAdvertisingAndListening without error
2017-03-22 12:44:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-(lldb) ,22 12:44:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":nul,l,"networkType":null}})'
2017-03-22 12:44:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
(lldb) ,ok 72 Can call startUpdateAdvertisingAndListening twice without error
,# teardown
(lldb) ,2017-03-22 12:44:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
,2017-03-22 12:44:37 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
(lldb) ,2017-03-22 12:44:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
,ok 73 Should be able to call stopListeningForAdvertisements in teardown
(lldb) ,2017-03-22 12:44:37 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:37 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state),.'
ok 74 Should be able to call stopAdvertisingAndListening in teardown
,2017-03-22 12:44:37 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-22 12:44:37 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-22 12:44:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-22 12:44:37 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-22 12:44:37 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-22 12:44:37 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-22 12:44:37 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-22 12:44:37 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
,2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state)(lldb) ,.'
ok 75 Can call startUpdateAdvertisingAndListening without error
2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:39 - INFO thaliMobile:, 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 76 Can call stopAdvertisingAndListening without error
(lldb) ,# teardown
,2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
(lldb) ,2017-03-22 12:44:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 77 Should be able to call stopListeningForAdvertisements in teardown
2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'discoveryAdverti,singStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2017-03-22 12:44:39 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 78 Should be able to call stopAdvertisingAndListening in teardow,n
2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
,2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
(lldb) ,2017-03-22 12:44:39 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
,2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
(lldb) ,2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
,2017-03-22 12:44:39 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
(lldb) ,# setup
,# peerAvailabilityChange is called
(lldb) ,2017-03-22 12:44:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-22 12:44:40 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-22 12:44:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt(lldb) ,ateUpdate (was in stopped state).'
ok 79 Can call startUpdateAdvertisingAndListeningwithout error
2017-03-22 12:44:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
,2017-03-22 12:44:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-03-22 12:44:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 80 Can call startListeningForAdvertisements without error
(lldb) ,ok 81 peers must be an array
ok 82 peers must not be zero-length
ok 83 peer must have only peerIdentifier, peerAvailable and generation properties
ok 84 peerIdentifier must be a string
ok 85 generation must be a number
(lldb) ,# teardown
,2017-03-22 12:44:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-22 12:44:44 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-22 12:44:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 86 Should be able to call stopListeningForAdvertisements in teardown
2017-03-22 12:44:44 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'(lldb) ,
2017-03-22 12:44:44 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 87 Should be able to call stopAdvertisingAndListening in teardown
2017-03-22 12:44:44 - DEBUG thaliMobileNativeWrapper: 'Method peerAvaila,bilityChanged registered to native'
2017-03-22 12:44:44 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
(lldb) ,2017-03-22 12:44:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectResolved registered to native'
(lldb) ,2017-03-22 12:44:44 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"cellular":"doNotCare","wifi":"on","bluetooth":"on","ssid":"NG700","bssid":"f4:f2:6d:22:99:3e","bluetoothLowEnergy":"on"}'
,2017-03-22 12:44:44 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
(lldb) ,2017-03-22 12:44:44 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
,2017-03-22 12:44:44 - DEBUG thaliMobileNativeWrapper: 'Method multiConnectConnectionFailure registered to native'
(lldb) ,2017-03-22 12:44:44 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
,# setup
(lldb) ,# Can connect to a remote peer
(lldb) ,2017-03-22 12:44:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2017-03-22 12:44:52 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) (lldb) ,did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecret":null,"networkType":null}})'
2017-03-22 12:44:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingSt,ateUpdate (was in stopped state).'
ok 88 Can call startUpdateAdvertisingAndListening without error
2017-03-22 12:44:52 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
(lldb) ,2017-03-22 12:44:52 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH","startArguments":{"router":null,"pskIdToSecre,t":null,"networkType":null}})'
2017-03-22 12:44:52 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 89 Can call startListeningForAdvertisements without error
(lldb) ,2017-03-22 12:44:53 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"BDD3B0DB-2D74-4657-90BD-EA614A9A02DC","generation":0}]'
,2017-03-22 12:44:53 - DEBUG thaliMobileNativeTestUtils: 'Issuing multiConnect for BDD3B0DB-2D74-4657-90BD-EA614A9A02DC (syncValue: xlRNRJEwy90a9nzVta8Ys31O4eWMxMuC)'
(lldb) ,2017-03-22 12:44:53 - DEBUG thaliMobileNativeTestUtils: 'Got 'multiConnect' callback'
,2017-03-22 12:44:53 - INFO testThaliMobileNative: 'Received peerAvailabilityChanged with peers: [{"peerAvailable":true,"peerIdentifier":"0F7BC885-750B-4D7A-82F5-AEDCBA9D6B9B","generation":0}]'
(lldb) ,libc++abi.dylib: terminating with uncaught exception of type NSException
(lldb) ,* thread #1: tid = 0x85e5f, 0x00000001910e1188 libsystem_kernel.dylib`mach_msg_trap + 8, queue = 'com.apple.main-thread'
  * frame #0: 0x00000001910e1188 libsystem_kernel.dylib`mach_msg_trap + 8
    frame #1: 0x00000001920de5d0 CoreFoundation`<redacted> + 192
    frame #2: 0x00000001920dc1ec CoreFoundation`<redacted> + 1132
    frame #3: 0x000000019200a2b8 CoreFoundation`CFRunLoopRunSpecific + 444
    frame #4: 0x0000000193abe198 GraphicsServices`GSEventRunModal + 180
    frame #5: 0x00000001980517fc UIKit`<redacted> + 684
    frame #6: 0x000000019804c534 UIKit`UIApplicationMain + 208
    frame #7: 0x00000001000e55ac ThaliTest`main + 76
    frame #8: 0x0000000190fed5b8 libdyld.dylib`<redacted> + 4

```
